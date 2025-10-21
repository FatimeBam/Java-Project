# Java-Project
# Auto detect text files and perform LF normalization
* text=auto
gitHub
public class App {
    public static void main(String[] args) {

        //  // Kokeile eri arvoja, esim. 10, 20, 70
        // int ika = 35;

        // // Tulostusehdot
        // if (ika >= 0 && ika < 18) {
        //     System.out.println("Olet alaikäinen");
        // } else {
        //     System.out.println("Olet aikuinen");
        // }
            int ika = 100;
            console.log("henkilön ikä on " + ika);



        // if (ika > 0 && ika < 18) {
        //     System.out.println("Olet alaikäinen");
        // } else if (ika >= 65) {
        //     System.out.println("Olet eläkeläinen");
        // } else {
        //     System.out.println("Olet aikuinen");
        // }
      
        console.log("henkilö on aikuinen");

        // if (ika > 0 && ika < 18) {
        //     System.out.println("Olet alaikäinen");
        console.log("henkilö on alaikänen");
        
        // } else if (ika >= 65) {

        //     if (ika >= 15) {
        //         System.out.println("Saat ajaa mopoa");
        //     }

        // } else if (ika >= 65) {
        //     System.out.println("Olet eläkeläinen");
        console.log("henkilö on eläkeläinen");
        cosole.log ("henkilö saa ajaa mopoa");

        // } else {
        //     System.out.println("Olet aikuinen");
        // }
         // Alaikäiset
        if (ika > 0 && ika < 18) {
            System.out.println("Olet alaikäinen");
            // Mopon ajoikä
            if (ika >= 15 && ika <= 17) {
                System.out.println("Saat ajaa mopoa");
            }

            // Kevan ajoikä
            if (ika >= 16 && ika <= 17) {
                System.out.println("Voit ajaa kevaria");
            }
        } 
        // Täysi-ikäinen juuri 18-vuotias
        else if (ika == 18) {
            System.out.println("Olet juuri tullut täysi-ikäiseksi");
            System.out.println("Saat ajaa autoa");
        } 
        // Aikuiset 19–64
        else if (ika > 18 && ika < 65) {
            System.out.println("Olet aikuinen");

            // Tasavuosikymmenet
            if (ika % 10 == 0) {
                System.out.println("Onnittelut tasavuosikymmenestä!");
            }

            // Keski-ikätoivotus 40–50-vuotiaille
            if (ika >= 40 && ika <= 50) {
                System.out.println("Parasta keski-ikää!");
            }

            // Varhaiseläke 58+
            if (ika >= 58) {
                System.out.println("Voit harkita varhaiseläkettä");
            }
        } 
        // Eläkeläiset 65+
        else if (ika >= 65) {
            System.out.println("Olet eläkeläinen");

            // Hyviä eläkepäiviä 65-vuotiaille
            if (ika == 65) {
                System.out.println("Hyviä eläkepäiviä!");
            }

            // Erityinen onnentoivotus 100-vuotiaille
            if (ika == 100) {
                System.out.println("Paljon onnea 100-vuotiaalle!");
                System.out.println("Toivotamme sinulle hyvää terveyttä!");
                System.out.println("Ja monta onnellista vuotta lisää!");
            }
        } 
       
    }
}
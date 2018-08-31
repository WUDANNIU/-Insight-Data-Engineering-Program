import java.io.File;
import java.util.LinkedList;
import java.util.List;
import java.util.Scanner;

public class prediction_validation {
    public static void main(String [] args) throws Exception{
        //path need to be changed, this is the path on my computer
        File actual = new File("/Users/peterhan/prediction-validation/input/actual.txt");
        File predicted = new File("/Users/peterhan/prediction-validation/input/predicted.txt");
        File window = new File("/Users/peterhan/prediction-validation/input/window.txt");
        Scanner actualSc = new Scanner(actual);
        Scanner predictedSc = new Scanner(predicted);
        Scanner windowSc = new Scanner(window);
        int windowInt = Integer.parseInt(windowSc.nextLine());
        List<String> actualData = new LinkedList<>();

        while (actualSc.hasNextLine()){
            String data = actualSc.nextLine();
            if (data.trim().length() > 0) {
                actualData.add(data);
            }
        }

        for (String data : actualData){
            System.out.println(data);
            String[] tokens = data.split("\\|");
            int time = Integer.parseInt(tokens[0]);
            System.out.println(time);
            String name = tokens[1];
            System.out.println(name);
            double price = Double.parseDouble(tokens[2]);
            System.out.println(price);
        }

        while (predictedSc.hasNextLine()){

                break;
        }





    }
}

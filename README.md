# ReadMeChickens
Excercise 3-2
public class Chickens02 {
    public static void main(String[] args) {
        // 1. Declare and initialize the tracking variables
        int mondayEggs = 100;
        int tuesdayEggs = 121;
        int wednesdayEggs = 117;

        double dailyAverage = (mondayEggs + tuesdayEggs + wednesdayEggs) / 3.0;

        double monthlyAverage = dailyAverage * 30;

        double monthlyProfit = monthlyAverage * 0.18;

        System.out.println("Daily Average:   " + dailyAverage);
        System.out.println("Monthly Average: " + monthlyAverage);
        System.out.println("Monthly Profit:  $" + monthlyProfit);
    }
}


public class Chickens01 { 
    public static void main(String[] args) { 

        int eggsPerChicken = 5;
        int chickenCount = 3;
        int totalEggs = 0;

        totalEggs += chickenCount * eggsPerChicken;

        chickenCount++;
        totalEggs += chickenCount * eggsPerChicken;

        chickenCount /= 2;
        totalEggs += chickenCount * eggsPerChicken;

        System.out.println(totalEggs); 
    } 
}

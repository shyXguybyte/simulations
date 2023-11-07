

package com.mycompany.simualtions;

import java.util.Scanner;

public class Simualtions { 

    public static void main(String[] args) {
        int RNnews;
        Scanner input = new Scanner(System.in);
        System.out.println("enter the number of daily purchased newspapers:");
        
        int dailyNPs = input.nextInt();
        double TotalProfit = 0;
        int day = 1;
        while(day <= 10){
        

            System.out.println("enter RN for news type:");
            RNnews = input.nextInt();
            String Type = "NULL";
            int RNdemand = 0;
            int demand = 0;
            
          //CASE GOOD
               if(RNnews >= 1 && RNnews <= 35)
               {
                    Type = "good";

                   System.out.println("enter RN for demand:");
                   RNdemand = input.nextInt();

                   if(RNdemand >= 1 && RNdemand <= 3)
                   {
                       demand = 40;
                   }
                   else if(RNdemand >= 4 && RNdemand <= 8)
                   {
                       demand = 50;
                   }
                    else if(RNdemand >= 9 && RNdemand <= 23)
                   {
                       demand = 60;
                   }
                     else if(RNdemand >= 24 && RNdemand <= 43)
                   {
                       demand = 70;
                   } 
                     else if(RNdemand >= 44 && RNdemand <= 78)
                   {
                       demand = 80;
                   }
                      else if(RNdemand >= 79 && RNdemand <= 93)
                   {
                       demand = 90;
                   }
                    else if(RNdemand >= 94 && RNdemand <= 100)
                   {
                       demand = 100;
                   }

               }

               //CASE FAIR

              else if(RNnews >= 36 && RNnews <= 80)
               {
                    Type = "fair";

                   System.out.println("enter RN for demand:");
                   RNdemand = input.nextInt();

                   if(RNdemand >= 1 && RNdemand <= 10)
                   {
                       demand = 40;
                   }
                   else if(RNdemand >= 11 && RNdemand <= 28)
                   {
                       demand = 50;
                   }
                    else if(RNdemand >= 29 && RNdemand <= 68)
                   {
                       demand = 60;
                   }
                     else if(RNdemand >= 69 && RNdemand <= 88)
                   {
                       demand = 70;
                   } 
                     else if(RNdemand >= 89 && RNdemand <= 96)
                   {
                       demand = 80;
                   }
                      else if(RNdemand >= 97 && RNdemand <= 100)
                   {
                       demand = 90;
                   }
                   

               }

               //CASE POOR

               else if(RNnews >= 81 && RNnews <= 100)
               {
                   Type = "poor";

                   System.out.println("enter RN for demand:");
                   RNdemand = input.nextInt();

                   if(RNdemand >= 1 && RNdemand <= 44)
                   {
                       demand = 40;
                   }
                   else if(RNdemand >= 45 && RNdemand <= 66)
                   {
                       demand = 50;
                   }
                    else if(RNdemand >= 67 && RNdemand <= 82)
                   {
                       demand = 60;
                   }
                     else if(RNdemand >= 83 && RNdemand <= 94)
                   {
                       demand = 70;
                   } 
                     else if(RNdemand >= 95 && RNdemand <= 100)
                   {
                       demand = 80;
                   }

               }
               
                   double CostofdailyNps = 33*dailyNPs;
                   double revenue = demand * 50;
                   double lostprofit = 0;
                   double scrap = 0;
                   double dailyProfit = 0;
                   if(demand > dailyNPs)
                   {
                       lostprofit = (demand-dailyNPs)*17;
                   }
                   else if(demand < dailyNPs)
                   {
                       scrap = (dailyNPs - demand)*7;
                   }
                   dailyProfit = revenue - CostofdailyNps + scrap;

                     System.out.println("day  NewsTypeRN  NewsType  DemandRN  Demand  Revenue   CostofNPs  LostProfit  ScrapRevenue  Dailyprofit");
                     System.out.println(day+"      "+RNnews+"         "+Type+"        "+RNdemand+"        "+demand+"     "+revenue/100+"$"+"     "+CostofdailyNps/100+"$"+"       "+lostprofit/100+"$"+"       "+scrap/100+"$"+"         "+dailyProfit/100+"$");
                     
                TotalProfit+=dailyProfit;
                day++;
      
            }
        System.out.println("TotalProfit = "+ TotalProfit/100+"$");
      
}        
}

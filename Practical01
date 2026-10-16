class Student {
    int RollNumber;
    String Name;
    int Marks1, Marks2, Marks3;

    Student(int RollNumber, String Name, int Marks1, int Marks2, int Marks3){
        this.RollNumber = RollNumber;
        this.Name = Name;
        this.Marks1 = Marks1;
        this.Marks2 = Marks2;
        this.Marks3 = Marks3;
    }
    int CalculateTotal(){
        return Marks1+Marks2+Marks3;
    }
    double CalculatePercentage(){
        return CalculateTotal()/3.0;
    }
    void displayDetails(){
        System.out.println("RollNumber :" +RollNumber);
        System.out.println("Name:" +Name);
        System.out.println("Marks1,Marks2,Marks3: "+Marks1 +","+Marks2 +","+Marks3);
        System.out.println("Total Marks:" +CalculateTotal());
        System.out.printf("Percentage: %.2f%%%n", CalculatePercentage());
        System.out.println("");
    }
    public static void main(String[] args) {
        Student s1 = new Student(101,"Pratham",85,88,79);
        Student s2 = new Student(102,"Mayank",99,99,99);
        Student s3 = new Student(103,"parul",89,93,92);
        s1.displayDetails();
        s2.displayDetails();
        s3.displayDetails();
    }
}

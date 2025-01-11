# Insert-and-print-student-details
Class Student {
    int rollno;
    String name;

    void insertRecord(int r, String n) {
        rollno = r;
        name = n;
    }

    void displayInformation() {
        System.out.println(rollno + " " + name);
    }
}

Public class TestStudent4 {
    Public static void main(String[] args) {
        Student student1 = new Student();
        Student student2 = new Student();

        student1.insertRecord(1, "Karan");
        student2.insertRecord(222, "Aryan");

        student1.displayInformation();
        student2.displayInformation();
    }
}

OUTPUT:

1 Karan
222 Aryan


package encapsulation;

public class Capsule {
    private int no;

    public int getno(){
        return no;
    }

    public void setno(int no){
        this.no=no;
    }

    public String getStudentName() {
        return studentName;
    }

    public void setStudentName(String studentName) {
        this.studentName = studentName;
    }

    public String getMiddleName() {
        return middleName;
    }

    public void setMiddleName(String middleName) {
        this.middleName = middleName;
    }

    public String getLastName() {
        return lastName;
    }

    public void setLastName(String lastName) {
        this.lastName = lastName;
    }

    public int getSrNum() {
        return srNum;
    }

    public void setSrNum(int srNum) {
        this.srNum = srNum;
    }

    public int getSubjects() {
        return subjects;
    }

    public void setSubjects(int subjects) {
        this.subjects = subjects;
    }

    public int getMarks() {
        return marks;
    }

    public void setMarks(int marks) {
        this.marks = marks;
    }

    public int getStandard() {
        return standard;
    }

    public void setStandard(int standard) {
        this.standard = standard;
    }

    private String studentName;
    private String middleName;
    private String lastName;
    private int srNum;
    private int subjects;
    private int marks;
    private int standard;

    public static void main(String[] args) {
        Capsule cap=new Capsule();
        cap.setStudentName("Vijay");
        cap.setMiddleName("maroti");
        cap.setLastName("kadpewad");
        cap.setSrNum(13);
        cap.setSubjects(6);
        cap.setMarks(88);
        cap.setStandard(9);
        cap.setno(1001);

        System.out.println("Student Name--"+cap.getStudentName());
        System.out.println("middle Name--"+cap.getMiddleName());
        System.out.println("Last name--"+ cap.getLastName());
        System.out.println("serial Number--"+ cap.getSrNum());
        System.out.println("Total Subject--"+ cap.getSubjects());
        System.out.println("Total Marks--"+cap.getMarks());
        System.out.println("Standard--"+cap.getStandard());
        System.out.println("number ="+cap.getno());
    }
}

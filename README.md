import java.util.ArrayList;
import java.util.List;

// Administrator class
class Administrator {
    public void viewRecord() {
        System.out.println("Viewing records");
    }

    public void manageChildInformation() {
        System.out.println("Managing child information");
    }

    public void dataAnalysisAndMakeDecision() {
        System.out.println("Performing data analysis and making decisions");
    }
}

// Children class
class Children {
    public void receiveVaccine() {
        System.out.println("Receiving vaccine");
    }
}

// Parent class
class Parent {
    public void receiveInformation() {
        System.out.println("Receiving information");
    }

    public void generateReport() {
        System.out.println("Generating report");
    }

    public void provideVaccine() {
        System.out.println("Providing vaccine");
    }

    public void receiveVaccinationReport() {
        System.out.println("Receiving vaccination report");
    }

    public void provideHealthcareHistory() {
        System.out.println("Providing healthcare history");
    }
}

// HealthcareProvider class
class HealthcareProvider {
    public void provideVaccine() {
        System.out.println("Providing vaccine");
    }

    public void generateReport() {
        System.out.println("Generating report");
    }

    public void receiveVaccinationReport() {
        System.out.println("Receiving vaccination report");
    }

    public void provideHealthcareHistory() {
        System.out.println("Providing healthcare history");
    }
}

// Main class
public class Main {
    public static void main(String[] args) {
        Administrator admin = new Administrator();
        admin.viewRecord();
        admin.manageChildInformation();
        admin.dataAnalysisAndMakeDecision();

        Children child = new Children();
        child.receiveVaccine();

        Parent parent = new Parent();
        parent.receiveInformation();
        parent.generateReport();
        parent.provideVaccine();
        parent.receiveVaccinationReport();
        parent.provideHealthcareHistory();

        HealthcareProvider provider = new HealthcareProvider();
        provider.provideVaccine();
        provider.generateReport();
        provider.receiveVaccinationReport();
        provider.provideHealthcareHistory();
    }
}

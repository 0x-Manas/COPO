# **Academic Outcome Tracker**  
A web-based tool designed to streamline course outcome (CO) and program outcome (PO) mapping for institutions, particularly for facilitating accreditation processes like NBA.

## **Purpose**  
The **Academic Outcome Tracker** assists faculty in evaluating student performance against predefined CO-PO matrices. By analyzing students' grades from continuous assessment tests (CATs), laboratory marks, and assignments, the system determines whether specific courses meet the required thresholds, aiding in institutional decision-making and accreditation compliance.

## **Key Features**  
- **Automated Calculations**: Generate course attainment results based on CAT scores, laboratory marks, and assignment grades.  
- **Student Management**:  
   - Upload student details (e.g., names and registration numbers) via **Excel sheets** or enter manually.  
   - Templates provided for easy data entry.  
- **Flexible Input Options**:  
   - Supports manual entry or bulk upload of CAT marks, laboratory marks, and assignments via **Excel sheets**.  
   - **Voice-based input** using Windows Cortana or voice access for hands-free data entry.  
- **Customizable Patterns**: Handles fixed or flexible assessment patterns for CATs.  
- **PDF and Excel Export**: Export results as PDF or Excel files for easy sharing and record-keeping.  
- **Visual Aids**: Includes screenshots and example templates to guide users.

## **Technologies Used**  
- **Frontend**: HTML, CSS, ReactJS  
- **Backend**: PHP, MySQL  
- **Excel Integration**: PHPExcel  
- **PDF Generation**: DOMPDF

## **How to Use**  
1. **Homepage**: Enter subject details (e.g., subject code, batch, etc.) and choose the assessment pattern (fixed or custom).  
2. **Upload Student Details**:  
   - Use the provided Excel template to upload student names, registration numbers, and their marks for CATs, laboratory, and assignments.  
   - Alternatively, manually enter details via the web interface.  
3. **Data Entry**:  
   - Option 1: Enter marks manually for CATs, laboratory, and assignments.  
   - Option 2: Upload an Excel sheet containing all marks.  
   - Option 3: Use voice commands to input marks.  
4. **Review & Submit**: Verify the entered data before submitting.  
5. **Results**:  
   - View the course attainment results on-screen.  
   - Download the results as a **PDF** or **Excel** file.

## **Use Case**  
This system is primarily developed for academic staff to monitor and evaluate course performance for accreditation purposes. By identifying areas where students struggle, the tool enables institutions to take corrective actions for course improvement.

## **Getting Started**  
To set up the project:  
1. Clone the repository:  
   ```bash
   git clone https://github.com/0x-Manas/COPO.git
2. **Set up a local server** (e.g., XAMPP) and import the database schema from `database.sql`.

3. **Run the application** on `localhost`.

### Template and Visual Aids

- **Templates:** An Excel file template is included in the `template` folder for uploading student details and marks.
- **Screenshots:** Refer to the `images` folder for step-by-step visuals of the system's functionality.

### Acknowledgments

This project was built with a focus on enhancing institutional efficiency and supporting accreditation processes.

---



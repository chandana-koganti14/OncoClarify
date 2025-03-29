# Workflow Documentation

## Step 1: Report Upload
- Users upload their cancer pathology reports via Tally Forms.
- Fields include:
  - User Role (Doctor, Nurse, Patient)
  - Report Type (Biopsy, Blood Test, etc.)

## Step 2: AI Analysis
- The uploaded report is sent to Gemini API for processing.
- Gemini extracts key details like diagnosis, stage, and treatment suggestions.
- The output is tailored based on the user role.

## Step 3: Personalized Summary Generation
- For Doctors: Technical insights and prognosis details.
- For Nurses: Actionable care steps and medication instructions.
- For Patients: Simplified explanations in supportive language.

## Step 4: Email Delivery
- Make.com automates the process of sending the simplified report via email.
- The email includes a brief summary of the full report.

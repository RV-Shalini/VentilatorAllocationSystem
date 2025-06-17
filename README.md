# Hospital Resource Management System

This project helps manage hospital equipment like ventilators by tracking patient arrivals and usage times. It shows if a ventilator is available for new patients and tells when one will be free if none are available.

## How to Use

1. Upload your patient data CSV file.
2. Run the code to load the data.
3. Enter new patient details when prompted.
4. The system will tell you if ventilator (Any hospital Resource) is available or when the next one will be free.

## Requirements

- Python 3
- pandas library (`pip install pandas`)

## CSV Format

Make sure your CSV file has these columns:

- Patient_ID
- Patient_Name
- Arrival_Date
- Arrival_Time
- Ventilator_Usage_Days
- Additional_Equipment

## License

This project is licensed under the MIT License.

# Attendance System

This is a simple Attendance System that records attendance and stores it in a CSV file. It provides a straightforward interface for taking attendance and managing records.

## Features

- Add new students to the attendance list.
- Mark students as present or absent.
- Save attendance records in a CSV file.
- View and manage past attendance records.

## Technologies Used

- Python

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/attendance-system.git
    ```

2. Navigate to the project directory:
    ```bash
    cd attendance-system
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```bash
    python attendance_system.py
    ```

2. Follow the on-screen prompts to take attendance, add new students, and manage records.

## CSV File Structure

The attendance records are stored in a CSV file with the following structure:

| Date       | Student ID | Name         | Status  |
|------------|------------|--------------|---------|
| 2024-07-01 | 123        | John Doe     | Present |
| 2024-07-01 | 124        | Jane Smith   | Absent  |
| 2024-07-02 | 123        | John Doe     | Absent  |
| 2024-07-02 | 124        | Jane Smith   | Present |

- **Date**: The date of the attendance record.
- **Student ID**: A unique identifier for each student.
- **Name**: The name of the student.
- **Status**: The attendance status, either "Present" or "Absent".

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any feature requests or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact [tiwariambrish81@gmail.com]

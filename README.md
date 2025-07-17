# ProjectProject Overview
Resume Uploader is a Django web application where users can submit and manage their resumes along with profile images. It is a good fit for job portals, recruitment platforms, or HR departments that need a simple way to collect and organize candidate data.

Key Features

Upload Functionality

Users can upload a resume (PDF or DOCX) and a profile photo (JPEG or PNG).

Django handles these files using FileField and ImageField in the backend.

Candidate Submission Form

The form contains text inputs (e.g., name, email), radio buttons (e.g., gender), checkboxes (e.g., skills), and a date picker for birthdate.

Server-side validation ensures that inputs follow the correct formats.

Profile Management and Viewing

The homepage displays a list of all submitted candidates, each with a thumbnail image.

A detailed view page shows full candidate information, a download link for the resume, and the profile image.

User Feedback and Notifications

The application uses Django’s message framework to inform users of successful uploads or validation errors.

Media Handling and Configuration

MEDIA_ROOT and MEDIA_URL are configured to serve uploads correctly in development.

Technologies and Tools Used

Django for models, forms, views, and message handling

Bootstrap for responsive layout and styling in templates

JavaScript: either jQuery UI DatePicker or HTML5 input type="date" to ensure date entries are in YYYY-MM-DD format

Django FileField and ImageField to manage file uploads, along with proper media configuration

Benefits and Use Cases

Accelerates the onboarding process by simplifying resume collection and display

Stores all candidate data in one central location for recruiters and HR staff

Ensures data quality through validation of input formats and file uploads

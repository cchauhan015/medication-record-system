💊 Medication Record System
This is a responsive and user-friendly web application designed to help doctors efficiently manage patient medication records locally in their browser. It features dynamic category and medication management, multi-language support (English and Gujarati), and persistent data storage using browser Local Storage.

✨ Features
Patient Medication Records: Add, view, edit, and delete patient medication records, including patient name, Sentam category, specific medication, dosage, and record date.

Dynamic Category Management:

Add New Categories: Easily create new Sentam categories (e.g., "Oncology," "Psychiatry") on the fly.

Manage Medications within Categories: Add, view, and delete specific medications for each category.

Delete Categories: Remove custom categories and all their associated medications with a confirmation step.

Centralized Management Dialog: All category and medication management functions are accessible via a dedicated dialog, opened directly from the Sentam Category dropdown in the main form.

Local Level Sentam Categories: Includes default categories relevant to common local ailments (e.g., Fever, Cold, Diarrhea, Vomiting) with pre-filled medications.

Multi-Language Support: Seamlessly switch between English and Gujarati for all application text. Your language preference is saved locally.

Local Storage Persistence: All patient records and custom categories/medications are saved directly in your browser's Local Storage, meaning your data remains even after closing and reopening the application.

Search Functionality: Quickly find records by patient name, medication, or category using the search bar.

Mobile-Friendly & Responsive Design: The application is built with Tailwind CSS to ensure an optimal viewing and interaction experience across various devices (desktops, tablets, and mobile phones).

User-Friendly Interface: Clear labels, intuitive workflows, touch-friendly interactive elements, and a "Scroll to Top" button for improved navigation.

🚀 How to Use
Open the Application: Simply open the index.html file (or run the React app in a development environment).

Select Language: Use the language dropdown in the top-right corner to switch between English and Gujarati.

Add/Edit Records:

Fill out the "Add New Medication Record" form with patient details.

To manage categories or medications, click the ⚙️ (Settings) icon next to the "Sentam Category" dropdown to open the management dialog.

To add a new category, use the "Add New Category" section in the dialog.

To manage medications within a category, select the category from "Select Category to Manage" in the dialog, then add or remove medications.

Existing records can be edited using the ✏️ (Edit) icon and deleted with the 🗑️ (Trash) icon next to each record.

Search Records: Use the search bar to filter records.

Data Persistence: Your data is automatically saved to your browser's Local Storage.

🛠️ Technologies Used
React: A JavaScript library for building user interfaces.

Tailwind CSS: A utility-first CSS framework for rapid UI development and responsive design.

Local Storage API: For client-side data persistence.

JavaScript (ES6+): Core programming language.

HTML5 & CSS3: For structuring and styling the web content.

Inline SVG Icons: For a lightweight and scalable icon system.

🎯 Future Enhancements (Ideas)
User Authentication: Implement a login system to secure data and support multiple doctors.

Cloud Storage: Integrate with a backend service (e.g., Firebase Firestore) for data backup and synchronization across devices.

Reporting/Analytics: Add features to generate reports or view statistics on medication usage.

Medication Search API: Integrate with an external API to get detailed information about medications.

Print Functionality: Allow printing of individual patient records or summaries.

# -Amazon-AppStream-2.0
Virtual Classroom Lab with Amazon AppStream 2.0

🎓 Project Title:
“Virtual Classroom Lab Using Amazon AppStream 2.0 for Remote Students”

✅ Project Overview:
The goal of this project is to create a virtual lab environment for students using Amazon AppStream 2.0, where they can remotely access high-performance desktop applications through a web browser. The project simulates how a school or college can provide students access to software like Visual Studio, MATLAB, or Photoshop — even if students have only low-spec laptops.

🔧 Tools & AWS Services Used:
Amazon AppStream 2.0

Amazon S3 (for saving student work)

AWS IAM (for access control)

Optional: AWS Directory Service (for user authentication)

📋 Project Steps:
1. Create an Amazon AppStream 2.0 Image
Launch a temporary streaming instance using a Windows base image.

Install a required application (e.g., Notepad++, Visual Studio Code, or GIMP).

Test the app to ensure it works.

Create an AppStream image from this configuration.

2. Create a Fleet and Stack
Create a fleet that uses the image (choose instance type based on app requirements).

Create a stack and associate it with the fleet.

Configure user access (using email invites or temporary user pool).

3. Enable File Storage (Optional)
Enable S3 integration so students can save their files to an S3 bucket.

Alternatively, use Google Drive or OneDrive integration if enabled.

4. Test Student Access
Use a test student email to access the streaming application via a web browser.

Demonstrate the user login, launching the app, using it, and saving work.

5. Document Use Cases and Benefits
Include screenshots, a video demo, or a presentation slide deck.

Highlight how it solves real-world problems like:

No installation needed.

Run apps on Chromebooks or mobile devices.

Same environment for all students.

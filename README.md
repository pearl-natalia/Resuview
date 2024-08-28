# Résuview

Résuview is an innovative augmented reality (AR) application, designed to enhance networking events. The hand-crafted AR glasses seamlessly display resumes next to individuals, creating a dynamic and interactive experience. 

<p align="center">
<img width="100%" alt="Screenshot 2024-01-21 at 9 03 17 PM" src="https://github.com/pearl-natalia/resuview/assets/145855287/b595bbf9-3af1-436f-8ccc-10027308fa25">
</p>

## Hardware

**1. Base:** Holds screens and lenses in place. Also Provides stability and support for the AR display components.

**2. Headset:** Holds the glasses component for AR visualization. Also Enables a hands-free experience during networking events.

**3. Mounts:** Secures hand-tracking cameras from Leap Motion and 6-degree-of-freedom tracking cameras from Intel.

**4. Optical Components:** Utilizes optical components from Combine Reality for an immersive AR experience.

**5. Screens:** Incorporates high-refresh-rate screens from BOE for clear and vibrant resume display.

<p align="center">
<img width="100%" alt="Screenshot 2024-01-21 at 9 03 17 PM" src="https://github.com/pearl-natalia/resuview/assets/145855287/d97ff807-41ff-42ac-abfa-0775d82a7e45">
</p>

## Software
**1. Website:** Allows subjects to input resume information through a form. Then stores real-time data in an SQL database for retrieval.

**2. PHP File:** Accepts data from the website form and inserts it into a MySQL table.

**3. QR Code Generator:** Generates a QR code with a unique ID corresponding to the submission.

**4. QR Code Scanner (C#):** Scans QR codes using the AR headset camera. Then retrieves the ID associated with the QR code.

**5. Unity Program P1:** Connects to the SQL database host. Then reads the ID from the QR code and fetches the corresponding resume data.

**6. Unity Program P2:** Displays formatted resume information in the AR environment. 

**7. AR Glasses:** Allows users to view resumes next to corresponding individuals, with hand tracking to resize/move the resume. 

<p align="center">
<img width="100%" alt="Screenshot 2024-01-21 at 9 07 52 PM" src="https://github.com/pearl-natalia/resuview/assets/145855287/64b1288f-ab2b-4108-9b5a-12f1f3ca9f7a">
</p>

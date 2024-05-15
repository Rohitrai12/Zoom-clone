# Zoom Clone

![Zoom Clone](https://private-user-images.githubusercontent.com/67959015/317983098-f09a8421-67d3-45ce-b9bc-a791cdc2774b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTU3NDYzNzYsIm5iZiI6MTcxNTc0NjA3NiwicGF0aCI6Ii82Nzk1OTAxNS8zMTc5ODMwOTgtZjA5YTg0MjEtNjdkMy00NWNlLWI5YmMtYTc5MWNkYzI3NzRiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MTUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTE1VDA0MDc1NlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWJlZDcyYWFmYzNhYThhOGNiNzhjYzUwZDQ4YjRjY2Y1ZTVkOTQ2ZGM3MDI5MTExMmZlYWUyNWRiNTkwYmQzNGImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.jnmwa91Cz75Zw8B7P5LvT3uTWxuu_0GLhHeGmaz0qzs)

🤖 **Introduction**

Built with the latest Next.js and TypeScript, this project replicates Zoom, a widely used video conferencing tool. It enables users to securely log in, create meetings and access various meeting functionalities such as recording, screen sharing, and managing participants.

⚙️ **Tech Stack**

- Next.js
- TypeScript
- Clerk
- getstream
- shadcn
- Tailwind CSS

🔋 **Features**

- **Authentication:** Implements authentication and authorization features using Clerk, allowing users to securely log in via social sign-on or traditional email and password methods, while ensuring appropriate access levels and permissions within the platform.
- **New Meeting:** Quickly start a new meeting, configuring camera and microphone settings before joining.
- **Meeting Controls:** Participants have full control over meeting aspects, including recording, emoji reactions, screen sharing, muting/unmuting, sound adjustments, grid layout, participant list view, and individual participant management (pinning, muting, unmuting, blocking, allowing video share).
- **Exit Meeting:** Participants can leave a meeting, or creators can end it for all attendees.
- **Schedule Future Meetings:** Input meeting details (date, time) to schedule future meetings, accessible on the 'Upcoming Meetings' page for sharing the link or immediate start.
- **Past Meetings List:** Access a list of previously held meetings, including details and metadata.
- **View Recorded Meetings:** Access recordings of past meetings for review or reference.
- **Personal Room:** Users have a personal room with a unique meeting link for instant meetings, shareable with others.
- **Join Meetings via Link:** Easily join meetings created by others by providing a link.
- **Secure Real-time Functionality:** All interactions within the platform are secure and occur in real-time, maintaining user privacy and data integrity.
- **Responsive Design:** Follows responsive design principles to ensure optimal user experience across devices, adapting seamlessly to different screen sizes and resolutions.
- **And many more, including code architecture and reusability.**

🤸 **Quick Start**

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository

```bash
git clone https://github.com/adrianhajdin/zoom-clone.git
cd zoom-clone

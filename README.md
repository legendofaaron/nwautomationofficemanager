
# Office Manager - Schedule Generator
<img width="1005" alt="light and dark mode " src="https://github.com/user-attachments/assets/3920a9bc-b4f9-43c5-8ece-803d06aeb412" />


Overview
Office Manager is a powerful, open-source administrative suite designed to streamline document management, schedule organization, and workplace productivity. By combining AI-driven automation with a local-first architecture, it offers a robust alternative to expensive cloud-based office tools for both commercial and personal use.

Features
Document Management: Create, edit, and organize business documents with integrated AI assistance.

Knowledge Base: Build a searchable, private company repository for internal procedures and data.

Office Management: Professional-grade tools for shift scheduling, team coordination, and task tracking.

Intelligent Assistant: An AI-powered co-pilot tailored to handle repetitive administrative tasks.

How to Edit This Code
You can customize the application to fit your specific business needs using the following methods:

Use Your Preferred IDE

To work locally, ensure you have Node.js & npm installed.

Clone the repository: git clone https://github.com/legendofaaron/nwautomationofficemanager.git

Navigate to the directory: cd nwautomationofficemanager

Install dependencies: npm install

Launch development server: npm run dev

Direct Browser Editing

GitHub Editor: Click the pencil icon on any file within the repository to make quick commits.

GitHub Codespaces: Launch a full cloud-based development environment by clicking Code > Codespaces > New codespace.

Technologies Used
Vite & React: For a fast, responsive user interface.

TypeScript: Ensuring code reliability and maintainability.

shadcn-ui & Tailwind CSS: Professional, modern styling.

Electron: Powering the native desktop experience.

Supabase: Managing secure, local-first data storage.

Deployment & Desktop Builds
Web Deployment

Building for Desktop

To package the app for offline desktop use:

Bash
# Build the web assets
npm run build

# Build for all desktop platforms
npx electron-builder build

# Build specifically for Apple Silicon (M1/M2/M3)
npx electron-builder build --mac --arm64
Note on Apple Silicon: The application is fully optimized for ARM64 architecture, providing native performance, reduced power consumption, and hardware acceleration for machine learning features on M-series chips.

Support & Contact
Support Development
If Office Manager adds value to your workflow, consider supporting continued development via PayPal.

Contact
For support or inquiries, please open an issue on the GitHub repository or reach out to the Northwestern Automation team at northwesternautomation@gmail.com.

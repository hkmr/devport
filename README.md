# DevPort - Developer Portfolio Platform**

**DevPort** is a full-stack web application designed to help developers create, manage, and showcase their professional portfolios effortlessly. Built with **Next.js (Frontend)** and **NestJS (Backend)**, the platform allows users to display their projects, skills, work experience, and contact information in a customizable and responsive portfolio.


## Key Features
✅ **User Authentication** – Secure signup/login with JWT & OAuth (GitHub, Google)  
✅ **Portfolio Customization** – Personalize themes, layouts, and sections  
✅ **Project Showcase** – Add projects with descriptions, tech stack, and live links  
✅ **Skills & Experience** – Highlight expertise with proficiency levels and work history  
✅ **Contact Integration** – Built-in contact form with email notifications
✅ **Education** - Add educational background, degrees, and certifications
✅ **Responsive & SEO-friendly** – Optimized for all devices and search engines


## Additional Features
✅ **Dashboard** - Personalized dashboard for managing portfolio content and tracking profile views.
✅ **Media Uploads** - Support for uploading images, resumes, and other relevant files.
✅ **Social Links** - Add links to GitHub, LinkedIn, Twitter, personal websites, etc.
✅ **SEO Optimization** - Portfolios are optimized for search engines.
✅ **Analytics** - Basic analytics on portfolio visits and engagement.
✅ **Export Options** - Download portfolio as PDF or print-friendly format.
✅ **Notifications** - Email notifications for profile updates, login alerts, etc.
✅ **Privacy Controls** - Users can set sections as public or private.


## Technology Stack
✅ **Frontend** -	NextJS, Tailwind CSS, react-hook-form
✅ **Backend** -	Node.js with NestJS
✅ **Database** -	PostgreSQL
✅ **Authentication** -	JWT, OAuth 2.0
✅ **Hosting** -	AWS
✅ **Storage** -	AWS S3


## API Endpoints

| Endpoint                | Method | Description                     | Auth Required |
|-------------------------|--------|---------------------------------|---------------|
| `/api/auth/signup`      | POST   | Register new user               | No            |
| `/api/auth/login`       | POST   | Authenticate user               | No            |
| `/api/portfolio`        | GET    | Get logged-in user's portfolio  | Yes           |
| `/api/portfolio`        | POST   | Create/update portfolio         | Yes           |
| `/api/portfolio/:id`    | GET    | View public portfolio by ID     | No            |
| `/api/projects`         | POST   | Add a new project               | Yes           |
| `/api/projects/:id`     | PUT    | Update project                  | Yes           |
| `/api/projects/:id`     | DELETE | Delete project                  | Yes           |


## Security Considerations
✅ Passwords are hashed and never stored in plain text.
✅ All sensitive endpoints require authentication.
✅ Input validation and sanitization to prevent XSS/SQL injection.
✅ HTTPS enforced for all data transmission.


## Future Enhancements
✅ **Custom Domain Support** - Allow users to connect their own domains.
✅ **Team Portfolios** - Enable group portfolios for teams or organizations.
✅ **Integrations** - Connect with third-party APIs (e.g., GitHub activity, blog feeds).
✅ **Advanced Analytics** - In-depth traffic and engagement stats.
✅ **AI Suggestions** - Recommend skills or projects to add based on user profile.

# My Static Blog with Outstatic and Next.js
This repository contains a simple, statically generated blog built with Next.js and Outstatic. The blog showcases how to efficiently generate static pages for optimal performance and SEO, leveraging the capabilities of modern JavaScript frameworks.

Features
Static Site Generation: All pages are pre-rendered at build time for faster load times and better SEO.
Markdown Support: Blog posts are written in Markdown, making it easy to create and manage content.
Responsive Design: The blog is fully responsive and looks great on all devices.
Custom Styling: Tailored styles using CSS Modules for a unique look and feel.
Getting Started
Prerequisites
Node.js (version 14 or higher)
npm or yarn
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/my-static-blog.git
cd my-static-blog
Install the dependencies:

bash
Copy code
npm install
Running the Development Server
To start the development server, run:

bash
Copy code
npm run dev
Your blog will be available at http://localhost:3000.

Building for Production
To build the static site for production, run:

bash
Copy code
npm run build
This command will generate the static files in the out directory.

Usage
Create new Markdown files in the posts directory to add new blog posts.
Customize your blog by editing the components in the components directory and styles in the styles directory.
Deploying
You can deploy the generated static site to any static hosting provider (e.g., Vercel, Netlify). Simply upload the contents of the out directory.

Contributing
Feel free to open issues or submit pull requests. Contributions are welcome!

License
This project is licensed under the MIT License. See the LICENSE file for details.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Favitorio%2Foutstatic%2Ftree%2Fmain%2Fexamples%2Fbasic-blog&env=OST_GITHUB_ID,OST_GITHUB_SECRET&project-name=outstatic-blog&repo-name=outstatic-blog&demo-title=Outstatic%20Blog%20Demo&demo-description=A%20statically%20generated%20blog%20example%20using%20Outstatic&demo-url=https%3A%2F%2Foutstatic-example-blog.vercel.app%2F&demo-image=https%3A%2F%2Foutstatic.com%2Fimages%2Foutstatic-demo.png&envDescription=API%20Keys%20needed%20for%20installation&envLink=https%3A%2F%2Foutstatic.com%2Fdocs%2Fenvironment-variables)

Please, visit our [getting started](https://outstatic.com/docs/getting-started) guide.
Don't forget to check the `.env.local.example` file for environment variables.

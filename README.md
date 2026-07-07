# nexus-hub

This website serves as the digital home for our club, including:


General club info (Home, About, Team)
Nexus Spectrum — a blog hub where members can publish and read articles
Nexus Narratives — a podcast hub where members can share and listen to episodes

club-website/
├── client/                 # Frontend
│   ├── index.html          # Home
│   ├── about.html
│   ├── team.html
│   ├── spectrum/           # Blog section
│   │   ├── index.html      # Blog landing/grid
│   │   ├── post.html       # Single post template
│   │   └── submit.html     # Submit a blog post
│   ├── narratives/         # Podcast section
│   │   ├── index.html      # Episode list
│   │   └── episode.html    # Single episode template
│   └── assets/
│       ├── css/
│       ├── js/
│       └── images/
├── server/                 # Backend (Node.js + Express)
│   ├── models/             # MongoDB schemas (Post, Episode, TeamMember)
│   ├── routes/             # API routes
│   └── server.js
├── .env.example             # Environment variable template
└── README.md



🛠️ Tech Stack

LayerTechnologyPurposeFrontendHTML, CSS, JavaScriptPages & UIBackendNode.js + ExpressAPI to handle blog/podcast data & form submissionsDatabaseMongoDB (via Mongoose)Stores blog posts, podcast episodes, team infoHostingTBD (e.g. Render / Vercel + MongoDB Atlas)Deployment


Check the Issues tab / Project board for assigned tasks
Create a branch per issue: git checkout -b feature/issue-name
Commit changes with clear messages
Open a Pull Request, linking the issue (Closes #issue-number)
Hania reviews and merges after approval


# Clone the repo
git clone <repo-url>
cd nexus-hub

# Install server dependencies
cd server
npm install

# Create your .env file (see .env.example)

# Run the server
npm run dev

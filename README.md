# Hey there! I'm Nico! 👋

I'm a software engineer and educator, working as a QA Engineer at Thinx. I love solving complex problems, and few things make me as happy as bug-free code. I'm also a dedicated member of Code Nation's community, and I support the organization by building curriculum, projects, and tools for students and staff. I graduated from Flatiron School's full stack software engineering program in December 2022, and have a background of six years in the world of nonprofit education. I'm passionate about community, learning, and teaching.

- 🔭 I’m currently building an ecommerce app for a friend's business. I'm also working on building some new tools for Code Nation staff and students.
- 🌱 I’m currently learning Python and leveling up my testing knowledge. 
- 💬 Talk to me about hockey, football, video games, Jeopardy, and weird New Jersey lore.
- 😄 Pronouns: he/him

### 💻 [Check out my portfolio website!](https://portfolio-nicogarbaccio.vercel.app/)

## Technology Stack:
<div>
<img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp; 
<img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg" title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/ruby/ruby-plain-wordmark.svg" title="Ruby" alt="Ruby" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/rails/rails-plain-wordmark.svg" title="Rails" alt="Rails" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original.svg" title="MongoDB" alt="MongoDB" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original-wordmark.svg" title="PostgreSQL" alt="PostgreSQL" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/tailwindcss/tailwindcss-plain.svg" title="Tailwind" alt="Tailwind" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/firebase/firebase-plain-wordmark.svg" title="Firebase" alt="Firebase" width="40" height ="40"/>&nbsp;
</div>

## Some of my recent projects

### 🏠 [Stay Awhile](https://github.com/nicogarbaccio/stay-awhile) 
### An online marketplace for short-term home rentals inspired by Airbnb
#### [Live Site](https://stay-awhile.vercel.app/) | [Demo]()
Stay Awhile is an online marketplace for short-term home rentals – essentially a re-skinned Airbnb. It's got a Next.js/React front end, and for data I leveraged Next.js 13 to implement routing, server-side rendering, and error handling. TypeScript was utilized to ensure strict typing of data models, API routes, and React components for more robust and maintainable code. I implemented client-side form validation using react-hook-form, server error handling using react-toast, and calendars with react-date-range. I also incorporated maps via React Leaflet, and used Prisma to define and generate the database schema. Fetched data was directly accessed from MongoDB database through server-side React components. The app also has a booking and reservation system with guest and owner reservation cancellation, property creation and deletion, and pricing calculation. The advanced search algorithm filters out properties that have a reservation in the user's desired date range, and a favorites system allows users to easily save and share their preferred properties with others.The page is fully responsive and was styled with Tailwind CSS, which made it really easy to make the app look like the real Airbnb! It's deployed on Vercel.

### 🏫 [ExplorED](https://github.com/nicogarbaccio/explored)
### An e-learning app that lets instructors and students share materials, create discussions, and more
#### [Live Site](https://explored.onrender.com) | [Demo](https://www.loom.com/share/8da5fe90c42d495d924c220ce23c1f81)
ExplorED is an e-learning app that that makes it easy for instructors to share materials, create discussions, and more with students. I built this app for my capstone project at Flatiron School. Having a background in education and having used multiple platforms as a teacher and as a student, this is something I've wanted to build for a while. I built it solo and from scratch, so I'm pretty proud of it! It's got a React front end and a Rails back end. I customized a database schema using Postgres and implemented the MVC pattern in Ruby on Rails, which made the app scalable and efficient. To allow for file management, I integrated ActiveStorage, which enables instructors to upload materials and students to download them. For user authentication, I utilized BCrypt, which allows for different levels of authorization for instructors and student. And finally, I styled the app using Tailwind CSS, which makes it look great and easy to navigate (I especially love how the dropdown came out). 

### 💬 [Slouch](https://github.com/nicogarbaccio/slouch) 
### A single-page, lightweight version of the messaging app Slack 
#### [Live Site](https://slouch-e6459.web.app/)
Slouch is a single-page, lightweight version of the messaging app Slack. I built the front end with React and Redux, while the backend is powered by     Firebase, where it's also deployed. While I knew React already, I wanted to use new libraries while I built this, and doing so really showed me the power of Redux and Firebase (and Firebase hooks), as well as how easy styling becomes with Styled Components. I took advantage of Firebase hooks to support channel creation and provide Google authentication, which makes logging in unbelievably easy, quick, and secure. Redux fit in perfectly with the app, allowing users to seamlessly move from channel to channel. Last but not least, Styled Components and Material UI were used to create a sleek user interface that looks pretty close to the real Slack. While this is still a work in progress (I'm currently working on implementing DMs and the ability to send images), I'm really happy with how clean and easy to read this code is, and how much is going on in a very manageable amount of lines of code. 

### 🎶 [Groovehound](https://github.com/nicogarbaccio/groovehound) 
### A concert tracker that lets users find upcoming concerts and keep track of the ones they've been to
#### [Demo](https://www.loom.com/share/98d9737320164a4db5673c7f81a60d64)
Groovehound is a concert tracking website which allows users to easily find upcoming concerts and keep a record of the ones they've been to. It's got a React front end and a Rails back end. This was my first project built on Rails and PostgreSQL, and it really showed me the power of Rails associations, BCrypt, and building reusable components. My teammates and I built the database using PostgreSQL, which made it easy to create and store data about users, bands, concerts, and venues (and we had a lot of it). My favorite feature that I built is the For You feature, which utilizes the data to show upcoming concerts in the state and/or city that the user lives in and matches with genres or bands the user likes. It also allows the user to explore all upcoming concerts outside of their city and state. 

## 📫 How to reach me
### [Email](mailto:garbaccio20@gmail.com) | [LinkedIn](https://www.linkedin.com/in/nicogarbaccio/) | [Medium](https://medium.com/@nicogarbaccio)

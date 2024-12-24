<h1>Blog Application</h1>

  <h2>Overview</h2>
  <p>This is a simple <strong>Blog Application</strong> built with <strong>Laravel</strong> made for summer training by <strong>Ali Hasan Siam</strong>. It allows users to create, edit, and delete blog posts. The project also includes an admin dashboard for managing blog content.</p>

  <hr>

  <h2>Features</h2>
  <ul>
    <li>User Authentication (Login, Register, Logout).</li>
    <li>User Dashboard for managing posts.</li>
    <li>CRUD Operations for blog posts (Create, Read, Update, Delete).</li>
    <li>Responsive Design with <strong>Bootstrap</strong>.</li>
    <li>Email Notifications for updates and alerts.</li>
    <li>Version Control with <strong>Git and GitHub</strong>.</li>
  </ul>

  <hr>

  <h2>Technologies Used</h2>
  <ul>
    <li><strong>Backend:</strong> Laravel 10 (PHP Framework).</li>
    <li><strong>Styling:</strong> Bootstrap and CSS.</li>
    <li><strong>Database:</strong> MySQL.</li>
    <li><strong>Version Control:</strong> Git and GitHub.</li>
  </ul>

  <hr>

  <h2>Installation</h2>
  <ol>
    <li><strong>Clone the Repository</strong>
      <pre><code>git clone https://github.com/Eng-Ali-Seyam/Simple-Blog</code></pre>
    </li>
    <li><strong>Install Dependencies</strong>
      <pre><code>composer install
      npm install</code></pre>
    </li>
    <li><strong>Environment Setup</strong>
      <pre><code>cp .env.example .env</code></pre>
    </li>
    <li><strong>Generate Application Key</strong>
      <pre><code>php artisan key:generate</code></pre>
    </li>
    <li><strong>Configure Database</strong>
      <p>Update the database settings in the <code>.env</code> file:</p>
      <pre><code>DB_CONNECTION=mysql
      DB_HOST=127.0.0.1
      DB_PORT=3306
      DB_DATABASE=blog_db
      DB_USERNAME=root
      DB_PASSWORD=</code></pre>
    </li>
    <li><strong>Migrate Database</strong>
      <pre><code>php artisan migrate</code></pre>
    </li>
    <li><strong>Seed Database (Optional)</strong>
      <pre><code>php artisan db:seed</code></pre>
    </li>
    <li><strong>Run the Application</strong>
      <pre><code>php artisan serve</code></pre>
    </li>
  </ol>

  <hr>

  <h2>Usage</h2>
  <p><strong>User Dashboard:</strong></p>
  <ul>
    <li>Access the user panel by logging in as an regitered user.</li>
    <li>Manage blog posts, edit content, and delete unnecessary posts.</li>
  </ul>

  <p><strong>Frontend:</strong></p>
  <ul>
    <li>Users can browse published posts, view details, and interact with the blog.</li>
  </ul>

  <hr>
  </ul>

  <hr>
  <p>Run the tests using PHPUnit:</p>
  <pre><code>php artisan test</code></pre>

  <hr>

  <h2>Future Enhancements</h2>
  <ul>
    <li>Add comment and like functionalities.</li>
    <li>Implement pagination for posts.</li>
    <li>Include advanced filtering and search features.</li>
    <li>Improve SEO optimization.</li>
    <li>Add multi-language support.</li>
  </ul>

  <hr>

  <h2>Contributors</h2>
  <p><strong>Ali Siam</strong> – Backend and Frontend Developer.</p>

  <hr>

  <h2>License</h2>
  <p>This project is open-source and available under the <strong>MIT License</strong>.</p
# SimpleSNS

SimpleSNS is Social Network Service which focus on clean and intuitive interface, making it easy to connect, share, and discover.

Core Features:
- Post
- Follow
- Live Search
- Chatroom

## Installation

**Install project dependencies:**

`composer install`

`npm install`

**Copy .env from Example and Edit:**

`cp .env.example .env`

**Generate a new application key:**

`php artisan key:generate`

**Copy Database Seeders from Examples and Edit:**

`cp database/seeders/AdminSeeder.php.example database/seeders/AdminSeeder.php`

**Run database migrations:**

`php artisan migrate --seed`

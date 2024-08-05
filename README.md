# Website for [gappc.net](https://gappc.net)

This project contains the website for [gappc.net](https://gappc.net). It is built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com).

## 🚀 Quick start

Clone the repository, install the dependencies and run the development server:

```sh
# Clone the repository
git clone https://github.com/gappc/gappc-website.git

# Change into the project directory
cd gappc-website

# Install the dependencies
npm install

# Run the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Production build

To create a production build, run:

```sh
npm run build
```

This will create a `dist` directory with the production build.

### Production build with Docker

To create a production build with Docker, run:

```sh
docker run -it --rm -u $UID -v ./:/app node:lts sh -c "cd /app && npm ci && npm run build"
```

Note that the current directory is mounted into the Docker container, so the build artifacts will be available on the host machine.

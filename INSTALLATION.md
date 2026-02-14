# Installation Instructions

## System Requirements
- Node.js >= 14.x
- npm >= 6.x
- Docker (if using Docker setup)

## Steps to Install

### 1. Clone the Repository
To clone the repository, open your terminal and run the following command:

```bash
git clone https://github.com/mujejdjjffj-cloud/MK.git
```

### 2. Navigate to the Project Directory
Change your directory to the newly cloned repository:

```bash
cd MK
```

### 3. Install Dependencies
Ensure you have Node.js and npm installed, then run:

```bash
npm install
```

### 4. Docker Setup (Optional)
If you prefer to use Docker, make sure Docker is installed on your system. You can run the following command to build the Docker image:

```bash
docker build -t mk .
```

Then, to run the container:

```bash
docker run -p 3000:3000 mk
```
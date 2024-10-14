# **AI Music App Admin**

This monorepo is set up using **Lerna** and **npm workspaces** to manage multiple packages within the repository.

## **Getting Started**

### **Initial Setup**

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   cd your-repo-directory
   ```

2. Install dependencies across all packages:

   ```bash
   npm install
   ```

3. Bootstrap the monorepo and link dependencies:

   ```bash
   npx lerna link
   ```

### **Running the Application**

- To run the **frontend** application from the root:

  ```bash
  npm run start:frontend
  ```

- To run the **backend** application from the root:

  ```bash
  npm run start:backend
  ```

### **Running Both Applications**

You can also run both applications simultaneously:

```bash
npm run start:all
```

## **Directory Structure**

```bash
my-monorepo/
│
├── apps/
│   ├── frontend/           # Frontend React application
│   └── backend/            # Backend API service
│
├── lerna.json              # Lerna configuration file
├── package.json            # Root package.json with npm workspaces
└── README.md               # Project documentation
```

## **License**

This project is licensed under the MIT License.
# Installation Documentation

This section contains step-by-step installation guides
based on my hands-on experience.

---

## Linux & HPC Installation Docs

### 1. Lustre File System Installation (Rocky Linux 9.4)

**Environment**
- OS: Rocky Linux 9.4
- MGS + MDT: 1 node
- OSS: 2 nodes
- Client: 1 node

**Steps**
1. Install Lustre packages
2. Configure MGS and MDT
3. Configure OSS and OST
4. Mount Lustre on client
5. Verify file system

**Common Issues**
- Target already formatted  
  → Fix: `wipefs -a /dev/<disk>`

---

### 2. OpenFOAM Installation

- Install dependencies
- Compile OpenFOAM
- Configure MPI
- Validate parallel run

---

### 3. Svelte Application Installation (Offline)

1. Download Node.js and NPM packages
2. Untar packages and create symbolic links
3. Download `my-svelte-app`
4. Extract and navigate to app directory
5. Install dependencies offline:
6. Start application:

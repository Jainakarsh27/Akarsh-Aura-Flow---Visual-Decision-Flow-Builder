# Akarsh-Aura-Flow---Visual-Decision-Flow-Builder
Workflow Builder is a visual tool that allows users to design and manage decision-based workflows with ease. Using a node-based interface, users can create action steps, define conditional branches, and control the flow from start to completion. This dashboard focuses on clarity, flexibility, and structured logic, enabling seamless workflow.
# Workflow Builder Dashboard
---

## 🚀 Live Demo
🔗 https://your-live-link.vercel.app

---

## 📦 GitHub Repository
🔗 https://github.com/your-username/workflow-builder

---

## 📌 Project Overview

The **Workflow Builder Dashboard** enables users to construct workflows by adding action steps, branching logic, and end nodes. Each workflow is represented as a structured tree, allowing clear visualization of sequential and conditional paths.

This project was built as part of a frontend engineering assignment to demonstrate:
- Data modeling
- React component design
- State management
- UI/UX decision-making

---

## ✨ Features

- 🔹 Visual workflow canvas
- 🔹 Start, Action, Branch (Condition), and End nodes
- 🔹 Add nodes dynamically at any point in the workflow
- 🔹 Edit node labels in real time
- 🔹 Delete nodes with automatic re-linking of children
- 🔹 Conditional branching (True / False paths)
- 🔹 Clean and minimal UI built from scratch (no UI libraries)

---

## 🧱 Node Types

| Node Type | Description |
|---------|------------|
| Start | Entry point of the workflow |
| Action | Represents a single operation or step |
| Branch | Conditional node with multiple paths |
| End | Terminates a workflow path |

---

## 🛠️ Tech Stack

- **React** (Functional Components + Hooks)
- **JavaScript**
- **HTML & CSS**
- **Vite / Create React App** (depending on setup)

> ❌ No UI libraries  
> ❌ No diagram or flow libraries  
> ❌ No backend or database

---

## 🧠 Architecture & State Management

- The workflow is stored as a tree-based JavaScript object
- Each node contains:
  - Unique ID
  - Type
  - Label
  - Child references
- React state manages the entire workflow structure
- Recursive rendering is used to display nested nodes

---

## 📂 Folder Structure


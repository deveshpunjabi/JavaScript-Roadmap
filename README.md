<div align="center">

# 🌟 JavaScript Mastery Roadmap 2025

<img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=22&duration=3000&pause=1000&color=F7DF1E&center=true&vCenter=true&width=600&lines=Master+JavaScript+from+Zero+to+Hero;Full-Stack+Development+Journey;Modern+Web+Development+2025;Build+Amazing+Projects" alt="Typing SVG" />

<br>

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=F7DF1E)](https://javascript.info/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)](https://vuejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org/)

<br>

![Stars](https://img.shields.io/github/stars/deveshpunjabi/JavaScript-Roadmap?style=social&logo=github)
![Forks](https://img.shields.io/github/forks/deveshpunjabi/JavaScript-Roadmap?style=social&logo=github)
![Issues](https://img.shields.io/github/issues/deveshpunjabi/JavaScript-Roadmap?style=social&logo=github)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)

<h3>🚀 Your Ultimate Guide to JavaScript Mastery</h3>
<p><i>From fundamentals to full-stack development - everything you need to become a JavaScript expert</i></p>

[🎯 Start Journey](#-interactive-roadmap) • [📚 Resources](#-curated-resources) • [🛠️ Projects](#-hands-on-projects) • [💼 Career](#-career-path) • [🏆 Challenges](#-coding-challenges)

</div>

---

## 🎯 Interactive Roadmap

<div align="center">

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor': '#f7df1e', 'primaryTextColor': '#000', 'primaryBorderColor': '#333', 'lineColor': '#333', 'secondaryColor': '#61dafb', 'tertiaryColor': '#4fc08d'}}}%%

graph TB
    A[🎯 JavaScript Fundamentals<br/>Variables, Functions, Scope] --> B[🔧 DOM Manipulation<br/>Events, Storage, APIs]
    B --> C[⚡ ES6+ Modern Features<br/>Promises, Async/Await, Modules]
    C --> D[🎨 Frontend Frameworks<br/>React, Vue, Angular]
    D --> E[🖥️ Backend Development<br/>Node.js, Express, APIs]
    E --> F[🗄️ Database Integration<br/>MongoDB, PostgreSQL, Redis]
    F --> G[🔐 Authentication & Security<br/>JWT, OAuth, HTTPS]
    G --> H[🧪 Testing & Quality<br/>Jest, Cypress, Unit Tests]
    H --> I[🚀 Deployment & DevOps<br/>Docker, CI/CD, Cloud]
    I --> J[📈 Performance & Monitoring<br/>Optimization, Analytics]
    
    style A fill:#f7df1e,stroke:#333,stroke-width:3px,color:#000
    style B fill:#61dafb,stroke:#333,stroke-width:2px,color:#000
    style C fill:#4fc08d,stroke:#333,stroke-width:2px,color:#000
    style D fill:#ff6b6b,stroke:#333,stroke-width:2px,color:#fff
    style E fill:#4ecdc4,stroke:#333,stroke-width:2px,color:#000
    style F fill:#45b7d1,stroke:#333,stroke-width:2px,color:#fff
    style G fill:#96ceb4,stroke:#333,stroke-width:2px,color:#000
    style H fill:#feca57,stroke:#333,stroke-width:2px,color:#000
    style I fill:#ff9ff3,stroke:#333,stroke-width:2px,color:#000
    style J fill:#54a0ff,stroke:#333,stroke-width:2px,color:#fff
```

</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="600">
</div>

---

## 📊 Learning Progress Tracker

<div align="center">

| Phase | Duration | Difficulty | Progress |
|-------|----------|------------|----------|
| 🎯 **JavaScript Basics** | 4-6 weeks | 🟢 Beginner | ![Progress](https://progress-bar.dev/0/?title=Start%20Here&width=200&color=f7df1e) |
| ⚡ **Modern ES6+** | 3-4 weeks | 🟡 Intermediate | ![Progress](https://progress-bar.dev/0/?title=Next%20Level&width=200&color=61dafb) |
| 🎨 **Frontend Frameworks** | 8-10 weeks | 🟠 Advanced | ![Progress](https://progress-bar.dev/0/?title=Framework%20Master&width=200&color=4fc08d) |
| 🖥️ **Backend Development** | 6-8 weeks | 🔴 Expert | ![Progress](https://progress-bar.dev/0/?title=Full%20Stack&width=200&color=ff6b6b) |
| 🚀 **Production Ready** | 4-6 weeks | ⚫ Master | ![Progress](https://progress-bar.dev/0/?title=Production&width=200&color=333) |

</div>

---

## 🎨 Visual Learning Path

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="100">
</div>

### 🌟 Phase 1: Foundation Building

<details>
<summary><b>🎯 JavaScript Fundamentals (Weeks 1-6)</b></summary>

<div align="center">
<img src="https://media.giphy.com/media/ln7z2eWriiQAllfVcn/giphy.gif" width="300">
</div>

#### Week 1-2: Core Concepts
```javascript
// 🎯 Variables & Data Types
let message = "Hello JavaScript!";
const PI = 3.14159;
var isLearning = true;

// 🎯 Functions Revolution
const greet = (name) => `Welcome ${name}! 🚀`;
const calculate = (a, b, operation) => {
  const operations = {
    add: () => a + b,
    multiply: () => a * b,
    power: () => Math.pow(a, b)
  };
  return operations[operation]?.() || "Invalid operation";
};
```

#### Week 3-4: Control Flow & Arrays
```javascript
// 🎯 Modern Array Methods
const numbers = [1, 2, 3, 4, 5];
const processed = numbers
  .filter(n => n % 2 === 0)        // [2, 4]
  .map(n => n * n)                 // [4, 16]
  .reduce((sum, n) => sum + n, 0); // 20

// 🎯 Object Destructuring Magic
const user = { name: "Alice", age: 25, city: "NYC" };
const { name, ...rest } = user;
console.log(`${name} lives in ${rest.city}`);
```

#### Week 5-6: DOM Mastery
```javascript
// 🎯 Modern DOM Manipulation
const createCard = (data) => {
  const card = document.createElement('div');
  card.className = 'card animate-fadeIn';
  card.innerHTML = `
    <h3>${data.title}</h3>
    <p>${data.description}</p>
    <button onclick="handleClick('${data.id}')">Action</button>
  `;
  return card;
};

// 🎯 Event Delegation
document.addEventListener('click', (e) => {
  if (e.target.matches('.card button')) {
    animateCard(e.target.closest('.card'));
  }
});
```

</details>

### ⚡ Phase 2: Modern JavaScript

<details>
<summary><b>⚡ ES6+ Features & Async Programming (Weeks 7-11)</b></summary>

<div align="center">
<img src="https://media.giphy.com/media/3oKIPnAiaMCws8nOsE/giphy.gif" width="300">
</div>

#### Advanced Features Showcase
```javascript
// 🎯 Async/Await Mastery
const fetchUserData = async (userId) => {
  try {
    const [user, posts, followers] = await Promise.all([
      fetch(`/api/users/${userId}`).then(r => r.json()),
      fetch(`/api/posts?userId=${userId}`).then(r => r.json()),
      fetch(`/api/followers/${userId}`).then(r => r.json())
    ]);
    
    return { user, posts, followers };
  } catch (error) {
    console.error('💥 Error fetching data:', error);
    throw new Error('Failed to load user data');
  }
};

// 🎯 Modern Class Syntax
class DataManager {
  #privateData = new Map();
  
  constructor(config) {
    this.config = { timeout: 5000, ...config };
  }
  
  async #authenticate() {
    // Private method implementation
  }
  
  get stats() {
    return {
      entries: this.#privateData.size,
      lastUpdate: this.lastModified
    };
  }
}
```

</details>

### 🎨 Phase 3: Frontend Frameworks

<details>
<summary><b>🎨 React, Vue & Modern Frontend (Weeks 12-22)</b></summary>

<div align="center">
<img src="https://media.giphy.com/media/eNAsjO55tPbgaor7ma/giphy.gif" width="300">
</div>

#### React Hooks Mastery
```jsx
// 🎯 Custom Hooks
const useLocalStorage = (key, initialValue) => {
  const [storedValue, setStoredValue] = useState(() => {
    try {
      const item = window.localStorage.getItem(key);
      return item ? JSON.parse(item) : initialValue;
    } catch (error) {
      return initialValue;
    }
  });

  const setValue = (value) => {
    try {
      setStoredValue(value);
      window.localStorage.setItem(key, JSON.stringify(value));
    } catch (error) {
      console.error('Error saving to localStorage:', error);
    }
  };

  return [storedValue, setValue];
};

// 🎯 Component with Suspense
const UserProfile = ({ userId }) => {
  const user = useSWR(`/api/users/${userId}`, fetcher, {
    suspense: true,
    revalidateOnFocus: false
  });

  return (
    <div className="profile-card">
      <img src={user.avatar} alt={user.name} loading="lazy" />
      <h2>{user.name}</h2>
      <p>{user.bio}</p>
    </div>
  );
};
```

</details>

---

## 🛠️ Hands-on Projects

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="400">
</div>

### 🚀 Project Showcase

| Project | Level | Tech Stack | Live Demo | Source |
|---------|-------|------------|-----------|---------|
| 🎮 **Interactive Game Hub** | 🟢 Beginner | `HTML` `CSS` `JS` | [🔗 Demo](https://js-game-hub.netlify.app) | [📁 Code](./projects/game-hub) |
| 🌤️ **Weather Dashboard** | 🟡 Intermediate | `React` `API` `Charts` | [🔗 Demo](https://weather-dash.vercel.app) | [📁 Code](./projects/weather-app) |
| 💬 **Real-time Chat App** | 🟠 Advanced | `Node.js` `Socket.io` `MongoDB` | [🔗 Demo](https://chat-app-demo.herokuapp.com) | [📁 Code](./projects/chat-app) |
| 🛒 **E-commerce Platform** | 🔴 Expert | `Next.js` `Stripe` `PostgreSQL` | [🔗 Demo](https://shop-demo.vercel.app) | [📁 Code](./projects/ecommerce) |

<div align="center">

### 🎯 Project Ideas by Category

<table>
<tr>
<td width="50%">

#### 🎮 **Interactive & Fun**
- 🎲 Dice Rolling Simulator
- 🎯 Memory Card Game
- 🎵 Music Player
- 🎨 Drawing Canvas
- 🎪 Animation Showcase
- 🎰 Slot Machine
- 🧩 Puzzle Games
- 🎮 2D Platformer

</td>
<td width="50%">

#### 💼 **Business & Productivity**
- 📊 Analytics Dashboard
- 💰 Expense Tracker
- 📅 Calendar App
- 📝 Note Taking App
- 🏃‍♂️ Habit Tracker
- 💳 Invoice Generator
- 📈 Stock Portfolio
- 🏢 CRM System

</td>
</tr>
<tr>
<td width="50%">

#### 🌐 **Social & Communication**
- 💬 Chat Application
- 📱 Social Media Feed
- 🎥 Video Calling App
- 📧 Email Client
- 🗳️ Polling App
- 👥 Team Collaboration
- 📰 News Aggregator
- 🎭 Forum Platform

</td>
<td width="50%">

#### 🔧 **Developer Tools**
- 🎨 Code Editor
- 🔍 API Testing Tool
- 📊 Performance Monitor
- 🎯 Regex Tester
- 🎨 Color Palette Generator
- 📏 Unit Converter
- 🎭 Mock Data Generator
- 🔐 Password Manager

</td>
</tr>
</table>

</div>

---

## 📚 Curated Resources

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="400">
</div>

### 🎥 Premium Video Content

<div align="center">

| Resource | Platform | Duration | Rating | Free |
|----------|----------|----------|--------|------|
| [🎯 JavaScript Crash Course](https://www.youtube.com/watch?v=hdI2bqOjy3c) | YouTube | 1.5h | ⭐⭐⭐⭐⭐ | ✅ |
| [⚡ Modern JavaScript](https://www.youtube.com/watch?v=2qDywOS7VAc) | YouTube | 6h | ⭐⭐⭐⭐⭐ | ✅ |
| [🎨 JavaScript30](https://javascript30.com/) | Wes Bos | 30 days | ⭐⭐⭐⭐⭐ | ✅ |
| [🚀 Node.js Complete Guide](https://www.youtube.com/watch?v=fBNz5xF-Kx4) | YouTube | 12h | ⭐⭐⭐⭐⭐ | ✅ |
| [⚛️ React Complete Course](https://www.youtube.com/watch?v=bMknfKXIFA8) | YouTube | 10h | ⭐⭐⭐⭐⭐ | ✅ |

</div>

### 📖 Essential Reading Material

<details>
<summary><b>📚 Must-Read Books (Click to expand)</b></summary>

#### 🏆 **Beginner Friendly**
- 📘 [**Eloquent JavaScript**](https://eloquentjavascript.net/) - *Marijn Haverbeke*
  - 🎯 Perfect for beginners
  - 💡 Interactive examples
  - 🆓 Completely free online

- 📗 [**You Don't Know JS**](https://github.com/getify/You-Dont-Know-JS) - *Kyle Simpson*
  - 🎯 Deep dive into JS concepts
  - 💡 6-book series
  - 🆓 Open source

#### 🚀 **Advanced Level**
- 📙 [**JavaScript: The Good Parts**](https://www.oreilly.com/library/view/javascript-the-good/9780596517748/) - *Douglas Crockford*
- 📕 [**Secrets of the JavaScript Ninja**](https://www.manning.com/books/secrets-of-the-javascript-ninja-second-edition) - *John Resig*

</details>

### 🌟 Interactive Platforms

<div align="center">

[![freeCodeCamp](https://img.shields.io/badge/-freeCodeCamp-0A0A23?style=for-the-badge&logo=freecodecamp&logoColor=white)](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/)
[![Codecademy](https://img.shields.io/badge/-Codecademy-1F4788?style=for-the-badge&logo=codecademy&logoColor=white)](https://www.codecademy.com/learn/introduction-to-javascript)
[![MDN](https://img.shields.io/badge/-MDN_Web_Docs-000000?style=for-the-badge&logo=mdnwebdocs&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![JavaScript.info](https://img.shields.io/badge/-JavaScript.info-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://javascript.info/)

</div>

---

## 💡 Advanced Concepts Visualized

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284136-03988914-d42b-4505-b9fe-f8b7c5bede3e.gif" width="400">
</div>

### 🧠 JavaScript Event Loop

```mermaid
graph LR
    A[Call Stack] --> B{Stack Empty?}
    B -->|Yes| C[Event Loop]
    C --> D[Callback Queue]
    D --> E[Microtask Queue]
    E -->|Priority| C
    C --> F[Execute Callback]
    F --> A
    B -->|No| G[Execute Function]
    G --> A
    
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style C fill:#bbf,stroke:#333,stroke-width:2px
    style E fill:#bfb,stroke:#333,stroke-width:2px
```

### 🔄 Prototype Chain Visualization

```javascript
// 🎯 Understanding Prototypes
function Animal(name) {
  this.name = name;
}

Animal.prototype.speak = function() {
  return `${this.name} makes a sound`;
};

function Dog(name, breed) {
  Animal.call(this, name);
  this.breed = breed;
}

// 🔗 Prototype Chain
Dog.prototype = Object.create(Animal.prototype);
Dog.prototype.constructor = Dog;
Dog.prototype.bark = function() {
  return `${this.name} barks!`;
};

const myDog = new Dog("Buddy", "Golden Retriever");
console.log(myDog.speak()); // Inherited from Animal
console.log(myDog.bark());  // Own method
```

---

## 🏆 Coding Challenges

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284145-bf2c01a8-c448-4f1a-b911-99a7d494344f.gif" width="400">
</div>

### 🎯 Daily Challenge Calendar

<details>
<summary><b>🗓️ 30-Day JavaScript Challenge</b></summary>

#### Week 1: Foundation Building 🏗️
| Day | Challenge | Difficulty | Solution |
|-----|-----------|------------|----------|
| 1 | **Two Sum** | 🟢 Easy | [💡 View](./challenges/day01.js) |
| 2 | **Reverse String** | 🟢 Easy | [💡 View](./challenges/day02.js) |
| 3 | **Palindrome Check** | 🟢 Easy | [💡 View](./challenges/day03.js) |
| 4 | **FizzBuzz** | 🟢 Easy | [💡 View](./challenges/day04.js) |
| 5 | **Factorial** | 🟡 Medium | [💡 View](./challenges/day05.js) |
| 6 | **Prime Numbers** | 🟡 Medium | [💡 View](./challenges/day06.js) |
| 7 | **Array Chunking** | 🟡 Medium | [💡 View](./challenges/day07.js) |

#### Week 2: Data Structures 📊
| Day | Challenge | Difficulty | Solution |
|-----|-----------|------------|----------|
| 8 | **Valid Parentheses** | 🟡 Medium | [💡 View](./challenges/day08.js) |
| 9 | **Binary Search** | 🟡 Medium | [💡 View](./challenges/day09.js) |
| 10 | **Merge Sort** | 🟠 Hard | [💡 View](./challenges/day10.js) |
| 11 | **Quick Sort** | 🟠 Hard | [💡 View](./challenges/day11.js) |
| 12 | **Linked List** | 🟠 Hard | [💡 View](./challenges/day12.js) |
| 13 | **Binary Tree** | 🟠 Hard | [💡 View](./challenges/day13.js) |
| 14 | **Graph Traversal** | 🔴 Expert | [💡 View](./challenges/day14.js) |

</details>

### 🧩 Algorithm Visualizations

<div align="center">

```mermaid
graph TD
    A[Unsorted Array: 64, 34, 25, 12, 22, 11, 90] --> B[Bubble Sort Step 1]
    B --> C[Compare adjacent elements]
    C --> D[Swap if needed]
    D --> E[Continue until sorted]
    E --> F[Sorted Array: 11, 12, 22, 25, 34, 64, 90]
    
    style A fill:#ff9999
    style F fill:#99ff99
```

</div>

---

## 💼 Career Path

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">
</div>

### 📈 Salary Progression Chart

```mermaid
xychart-beta
    title "JavaScript Developer Salary Progression (USD)"
    x-axis [Junior, Mid-level, Senior, Lead, Principal]
    y-axis "Salary (K)" 0 --> 200
    bar [55, 85, 120, 160, 200]
```

<div align="center">

### 🎯 Career Tracks

<table>
<tr>
<td width="33%">

#### 🎨 **Frontend Specialist**
- 🎯 UI/UX Focus
- ⚛️ React/Vue Expert
- 🎨 CSS Wizard
- 📱 Mobile Development
- 💰 $60k - $140k

</td>
<td width="33%">

#### 🔧 **Full-Stack Developer**
- 🖥️ Frontend + Backend
- 🗄️ Database Design
- 🔐 Security Expert
- ☁️ Cloud Architecture
- 💰 $70k - $160k

</td>
<td width="33%">

#### 🏗️ **JavaScript Architect**
- 🎯 Technical Leadership
- 🏗️ System Design
- 👥 Team Management
- 📊 Performance Optimization
- 💰 $120k - $200k+

</td>
</tr>
</table>

</div>

### 🌟 Skills Roadmap Matrix

<div align="center">

| Skill Category | Junior | Mid-Level | Senior | Lead |
|---------------|--------|-----------|---------|------|
| **JavaScript Core** | ![Progress](https://progress-bar.dev/60/?title=Basic&width=100&color=4CAF50) | ![Progress](https://progress-bar.dev/80/?title=Advanced&width=100&color=2196F3) | ![Progress](https://progress-bar.dev/95/?title=Expert&width=100&color=FF9800) | ![Progress](https://progress-bar.dev/100/?title=Master&width=100&color=F44336) |
| **Frameworks** | ![Progress](https://progress-bar.dev/40/?title=Learning&width=100&color=4CAF50) | ![Progress](https://progress-bar.dev/75/?title=Proficient&width=100&color=2196F3) | ![Progress](https://progress-bar.dev/90/?title=Expert&width=100&color=FF9800) | ![Progress](https://progress-bar.dev/95/?title=Architect&width=100&color=F44336) |
| **Backend** | ![Progress](https://progress-bar.dev/20/?title=Basic&width=100&color=4CAF50) | ![Progress](https://progress-bar.dev/60/?title=Good&width=100&color=2196F3) | ![Progress](https://progress-bar.dev/85/?title=Advanced&width=100&color=FF9800) | ![Progress](https://progress-bar.dev/90/?title=Expert&width=100&color=F44336) |
| **DevOps** | ![Progress](https://progress-bar.dev/10/?title=Aware&width=100&color=4CAF50) | ![Progress](https://progress-bar.dev/40/?title=Basic&width=100&color=2196F3) | ![Progress](https://progress-bar.dev/70/?title=Good&width=100&color=FF9800) | ![Progress](https://progress-bar.dev/85/?title=Advanced&width=100&color=F44336) |
| **Leadership** | ![Progress](https://progress-bar.dev/5/?title=None&width=100&color=4CAF50) | ![Progress](https://progress-bar.dev/30/?title=Learning&width=100&color=2196F3) | ![Progress](https://progress-bar.dev/60/?title=Good&width=100&color=FF9800) | ![Progress](https://progress-bar.dev/90/?title=Strong&width=100&color=F44336) |

</div>

---

## 🎭 Interview Preparation

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284175-acc7d51c-4de4-428d-87c5-e5b9c6b97d7a.gif" width="400">
</div>

### 🔥 Top Interview Questions

<details>
<summary><b>⚡ Technical Deep Dive Questions</b></summary>

#### 🎯 **JavaScript Fundamentals**

**Q1: Explain the difference between `==` and `===`**
```javascript
// Type coercion with ==
console.log(5 == "5");   // true (string converted to number)
console.log(null == undefined); // true
console.log(0 == false); // true

// Strict equality with ===
console.log(5 === "5");   // false (different types)
console.log(null === undefined); // false
console.log(0 === false); // false

// Best Practice: Always use === unless you specifically need type coercion
```

**Q2: What is the Event Loop?**
```javascript
console.log("1"); // Synchronous

setTimeout(() => {
  console.log("2"); // Macrotask
}, 0);

Promise.resolve().then(() => {
  console.log("3"); // Microtask
});

console.log("4"); // Synchronous

// Output: 1, 4, 3, 2
// Microtasks have higher priority than macrotasks
```

**Q3: Implement a debounce function**
```javascript
function debounce(func, wait, immediate) {
  let timeout;
  
  return function executedFunction(...args) {
    const later = () => {
      timeout = null;
      if (!immediate) func.apply(this, args);
    };
    
    const callNow = immediate && !timeout;
    clearTimeout(timeout);
    timeout = setTimeout(later, wait);
    
    if (callNow) func.apply(this, args);
  };
}

// Usage
const debouncedSearch = debounce((query) => {
  console.log("Searching for:", query);
}, 300);
```

</details>

<details>
<summary><b>🧠 Problem Solving Challenges</b></summary>

#### 🎯 **Algorithm Implementation**

**Challenge 1: Flatten Nested Array**
```javascript
// Multiple approaches to flatten arrays
function flattenArray(arr) {
  // Method 1: Recursion
  const result = [];
  for (let item of arr) {
    if (Array.isArray(item)) {
      result.push(...flattenArray(item));
    } else {
      result.push(item);
    }
  }
  return result;
}

// Method 2: Built-in flat()
const flattened = arr.flat(Infinity);

// Method 3: Reduce
const flattenReduce = arr => arr.reduce(
  (acc, val) => acc.concat(Array.isArray(val) ? flattenReduce(val) : val), []
);
```

**Challenge 2: Deep Clone Object**
```javascript
function deepClone(obj, hash = new WeakMap()) {
  // Handle primitives and null
  if (obj === null || typeof obj !== "object") return obj;
  
  // Handle circular references
  if (hash.has(obj)) return hash.get(obj);
  
  // Handle dates
  if (obj instanceof Date) return new Date(obj.getTime());
  
  // Handle arrays
  if (Array.isArray(obj)) {
    const cloned = [];
    hash.set(obj, cloned);
    obj.forEach(item => cloned.push(deepClone(item, hash)));
    return cloned;
  }
  
  // Handle objects
  const cloned = {};
  hash.set(obj, cloned);
  Object.keys(obj).forEach(key => {
    cloned[key] = deepClone(obj[key], hash);
  });
  
  return cloned;
}
```

</details>

### 🎯 Mock Interview Simulator

<div align="center">

| Interview Type | Duration | Questions | Difficulty |
|---------------|----------|-----------|------------|
| 📱 **Phone Screen** | 30 min | 5-7 | 🟢 Basic |
| 💻 **Technical Round** | 60 min | 3-5 | 🟡 Medium |
| 🏗️ **System Design** | 45 min | 1-2 | 🟠 Hard |
| 👥 **Cultural Fit** | 30 min | 8-10 | 🟢 Soft Skills |

</div>

---

## 🛠️ Development Environment

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284160-0c8bcf35-05b4-46ad-b8af-7cd7fb29fb3a.gif" width="400">
</div>

### ⚡ Quick Setup Guide

```bash
# 🚀 Node.js & Package Managers
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
nvm install --lts
npm install -g yarn pnpm

# 🔧 Essential Global Tools
npm install -g @vue/cli create-react-app @angular/cli
npm install -g nodemon live-server http-server
npm install -g eslint prettier typescript

# 🧪 Testing & Quality Tools
npm install -g jest cypress @storybook/cli
npm install -g lighthouse @axe-core/cli
```

### 🎨 VS Code Power Setup

<div align="center">

| Extension | Purpose | Rating |
|-----------|---------|--------|
| 🎯 **JavaScript (ES6) snippets** | Code snippets | ⭐⭐⭐⭐⭐ |
| 🎨 **Prettier** | Code formatting | ⭐⭐⭐⭐⭐ |
| 🔍 **ESLint** | Code linting | ⭐⭐⭐⭐⭐ |
| 🌈 **Bracket Pair Colorizer** | Visual aid | ⭐⭐⭐⭐⭐ |
| 🔥 **Live Server** | Local development | ⭐⭐⭐⭐⭐ |
| 🎭 **GitLens** | Git integration | ⭐⭐⭐⭐⭐ |
| 🚀 **Thunder Client** | API testing | ⭐⭐⭐⭐⭐ |
| 🎯 **Auto Rename Tag** | HTML helper | ⭐⭐⭐⭐⭐ |

</div>

---

## 📊 Performance Metrics

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284180-8842b7c8-6c6b-4985-b39d-bfb8b6a8fb03.gif" width="400">
</div>

### 🎯 Code Quality Dashboard

<div align="center">

```mermaid
pie title JavaScript Skills Distribution
    "Fundamentals" : 25
    "Frameworks" : 20
    "Backend" : 15
    "Testing" : 10
    "DevOps" : 10
    "Soft Skills" : 20
```

</div>

### 🚀 Performance Optimization Checklist

<details>
<summary><b>⚡ Core Web Vitals Optimization</b></summary>

#### 🎯 **Largest Contentful Paint (LCP)**
```javascript
// Image optimization
const img = new Image();
img.loading = 'lazy';
img.decoding = 'async';
img.src = 'optimized-image.webp';

// Critical resource hints
const link = document.createElement('link');
link.rel = 'preload';
link.href = 'critical.css';
link.as = 'style';
document.head.appendChild(link);
```

#### 🎯 **First Input Delay (FID)**
```javascript
// Code splitting with dynamic imports
const loadModule = async () => {
  const { heavyFunction } = await import('./heavyModule.js');
  return heavyFunction;
};

// Web Workers for heavy computations
const worker = new Worker('computation.js');
worker.postMessage({ data: largeDataSet });
worker.onmessage = (e) => {
  console.log('Result:', e.data);
};
```

#### 🎯 **Cumulative Layout Shift (CLS)**
```css
/* Reserve space for images */
.image-container {
  aspect-ratio: 16 / 9;
  background: #f0f0f0;
}

/* Stable loading states */
.skeleton {
  background: linear-gradient(90deg, #f0f0f0 25%, #e0e0e0 50%, #f0f0f0 75%);
  background-size: 200% 100%;
  animation: loading 1.5s infinite;
}
```

</details>

---

## 🎨 Modern Design System

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284094-e50ceae2-de86-4dd3-a8e9-1abcc5a2e9b7.gif" width="400">
</div>

### 🌈 Color Palette

<div align="center">

| Color | Hex | Usage |
|-------|-----|-------|
| 🟡 **Primary** | `#F7DF1E` | JavaScript branding |
| 🔵 **Secondary** | `#61DAFB` | React elements |
| 🟢 **Success** | `#4CAF50` | Completed tasks |
| 🟠 **Warning** | `#FF9800` | Important notes |
| 🔴 **Error** | `#F44336` | Error states |
| ⚫ **Dark** | `#333333` | Text and borders |

</div>

### 🎭 Animation Library

```css
/* 🎯 Smooth transitions */
.animate-fadeIn {
  animation: fadeIn 0.6s ease-in-out;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

.animate-slideIn {
  animation: slideIn 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94);
}

@keyframes slideIn {
  from { transform: translateX(-100%); }
  to { transform: translateX(0); }
}

/* 🎯 Hover effects */
.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
}
```

---

## 🌟 Community & Support

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="400">

### 💬 Join Our Learning Community

[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/javascript)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/javascript_roadmap)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://reddit.com/r/javascript)
[![Stack Overflow](https://img.shields.io/badge/Stack%20Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/questions/tagged/javascript)

</div>

### 🤝 Contributing Guidelines

<details>
<summary><b>🔧 How to Contribute</b></summary>

#### 🎯 **Ways to Contribute**
1. 📝 **Content Creation**
   - Add new project ideas
   - Write tutorials
   - Create code examples
   - Update documentation

2. 🐛 **Issue Reporting**
   - Bug fixes
   - Typo corrections
   - Broken links
   - Outdated information

3. 🌟 **Feature Requests**
   - New sections
   - Tool recommendations
   - Resource additions
   - UI improvements

#### 🚀 **Contribution Process**
```bash
# 1. Fork the repository
gh repo fork deveshpunjabi/JavaScript-Roadmap

# 2. Create feature branch
git checkout -b feature/amazing-addition

# 3. Make changes and commit
git add .
git commit -m "✨ Add amazing new feature"

# 4. Push and create PR
git push origin feature/amazing-addition
gh pr create --title "✨ Amazing new feature"
```

</details>

---

## 📈 Analytics & Tracking

<div align="center">

### 📊 Repository Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=deveshpunjabi&show_icons=true&theme=radical)

### 🔥 Contribution Activity

![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=deveshpunjabi&theme=react-dark&hide_border=true)

### 🏆 Achievement Badges

![Trophy](https://github-profile-trophy.vercel.app/?username=deveshpunjabi&theme=darkhub&no-frame=true&margin-w=15)

</div>

---

## 🎯 Quick Navigation

<div align="center">

| Section | Quick Links |
|---------|-------------|
| 🎯 **Getting Started** | [Roadmap](#-interactive-roadmap) • [Resources](#-curated-resources) • [Setup](#-development-environment) |
| 🛠️ **Practice** | [Projects](#-hands-on-projects) • [Challenges](#-coding-challenges) • [Interview Prep](#-interview-preparation) |
| 💼 **Career** | [Salary Guide](#-career-path) • [Skills Matrix](#-skills-roadmap-matrix) • [Job Hunting](#-modern-design-system) |
| 🤝 **Community** | [Discord](https://discord.gg/javascript) • [Contribute](#-contributing-guidelines) • [Support](#-community--support) |

</div>

---

<div align="center">

## 🚀 Ready to Start Your JavaScript Journey?

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="300">

### Choose Your Path

[![Beginner Path](https://img.shields.io/badge/🎯_Start_with_Basics-4CAF50?style=for-the-badge&logoColor=white)](./beginner-path.md)
[![Intermediate Path](https://img.shields.io/badge/⚡_Level_Up_Skills-2196F3?style=for-the-badge&logoColor=white)](./intermediate-path.md)
[![Advanced Path](https://img.shields.io/badge/🚀_Master_Level-FF9800?style=for-the-badge&logoColor=white)](./advanced-path.md)

---

### 🌟 Star this repository to keep track of your progress!

![Stargazers](https://reporoster.com/stars/deveshpunjabi/JavaScript-Roadmap)

---

**Happy Coding! 🎉**

*Made with ❤️ by [Devesh Punjabi](https://github.com/deveshpunjabi)*

[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://deveshpunjabi.me/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/deveshpunjabi)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/deveshpunjabi)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6&height=100&section=footer" width="100%">
</div>

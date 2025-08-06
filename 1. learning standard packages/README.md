# Learn Go Standard Library (The Practical Way)

my personal learning repo for the Go standard library.

Instead of trying to learn all 200+ standard packages, I’ve created a focused roadmap that covers the **core packages** most Go developers use day-to-day. I'm learning by building simple programs using these packages, and sharing the journey here.

If you're also learning Go and want a practical starting point, feel free to use this plan!

---

## Category

### 1. Basics: I/O, Strings, Formatting
The absolute fundamentals of any Go program.

- `fmt` – print formatting
- `os` – working with files, env vars
- `io` – core I/O interfaces
- `strings` – manipulating text
- `strconv` – string ↔ number conversion

**Projects**:
- CLI calculator  
- Log file reader  
- Environment variable lister  

---

### 2. Files & Directories
For working with the filesystem.

- `os` – create, open, delete files
- `path/filepath` – OS-independent file paths
- `bufio` – buffered I/O for performance

**Projects**:
- File organizer  
- Recursive directory scanner  

---

### 3. HTTP & Networking
Build clients and servers using Go’s powerful net/http stack.

- `net/http` – web servers and clients
- `net/url` – parse and build URLs
- `encoding/json` – JSON handling
- `io` – reading/writing body streams

**Projects**:
- REST API server  
- API client (e.g., GitHub API fetcher)  
- Static file server  

---

### 4. Concurrency & Timing
Use Go's goroutines and synchronization tools.

- `sync` – WaitGroups, Mutex
- `context` – cancellation, deadlines
- `time` – timers, intervals

**Projects**:
- Concurrent web scraper  
- Worker pool  
- Timeout-aware job runner  

---

### 5. Testing & Logging
Make sure your code works and is maintainable.

- `testing` – unit tests
- `log` – structured logging
- `runtime/debug` – debug tools

**Projects**:
- Add tests/logging to all previous tools  
- Benchmarking small utilities  

---

### 6. Data Formats
Read/write JSON, CSV, XML — common data formats.

- `encoding/json`
- `encoding/csv`
- `encoding/xml`

**Projects**:
- CSV to JSON converter  
- Config loader in JSON or XML  

---

### 7. Useful Structures & Sorting
Built-in containers and helpers.

- `sort` – slice sorting
- `container/heap` – priority queues
- `container/list` – linked lists

**Projects**:
- Task manager with priority queues  
- Sorted todo list  

---

## 🗂️ Progress

| Category        | Status     |
|----------------|------------|
| Basics          | ✅ Done      |
| Filesystem      | ✅ Done      |
| HTTP & JSON     | 🔄 In progress |
| Concurrency     | 🔲    |
| Testing & Logs  | 🔲    |
| Data formats    | 🔲    |
| Structures      | 🔲    |


---

## 📚 Resources I Use

- [Go by Example](https://gobyexample.com/)
- [Go Standard Library Official Docs](https://pkg.go.dev/std)
- [Awesome Go](https://awesome-go.com/)

---

## 🤝 Contribute or Fork

If you find this helpful, feel free to fork, suggest improvements, or share your own focused learning path!

---

Thanks for stopping by! 🚀

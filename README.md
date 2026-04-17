# Vectorless RAG System Documentation

## Overview

The Vectorless RAG (Resource Allocation Graph) System is designed to manage resources dynamically without relying on vector representations. The focus of this system is to simplify resource allocation in environments where traditional vector-based methods may be cumbersome or inefficient.

## Features

- **Dynamic Allocation:** Easily allocate resources based on current needs without predefined vectors.
- **Efficiency:** Streamlined processes increase performance in resource management.
- **Flexibility:** Adaptable to various application requirements.

## Installation

To install the Vectorless RAG System, clone the repository:

```bash
git clone https://github.com/visnu64/Vectorless-RAG-system-.git
cd Vectorless-RAG-system-
```

## Usage

Here are the basic steps to use the Vectorless RAG System:

1. **Initialization**  
   Start by initializing the system and defining your resource types.
   
   ```python
   from rag_system import RAG

   rag = RAG()
   ```
   
2. **Adding Resources**  
   Add resources for management.
   
   ```python
   rag.add_resource('Resource1', capacity=10)
   ```

3. **Allocating Resources**  
   Allocate resources as required.
   
   ```python
   rag.allocate('Resource1', amount=5)
   ```

4. **Viewing Allocations**  
   You can view current resource allocations with:
   
   ```python
   rag.view_allocations()
   ```

## Examples

### Example Scenario

1. Initialize the RAG System.
2. Add resources and allocate them.
3. Display the current state of resource allocations.

```python
rag = RAG()
rag.add_resource('Resource1', capacity=10)
rag.add_resource('Resource2', capacity=20)

rag.allocate('Resource1', amount=5)
rag.allocate('Resource2', amount=10)

rag.view_allocations()
```

## Contributions

Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Developed by Visnu64

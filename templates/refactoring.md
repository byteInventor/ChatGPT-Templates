# Refactoring Template

Use this template when you need help cleaning up messy code, improving code quality, and implementing best practices.

## Template

```
Here's messy code → make it clean, modular, type-safe, tested, with logging.

**Current Code:**
[paste your code here]

**Language/Framework:** [e.g., JavaScript/React, Python/Django, Java/Spring]

**Specific Issues:** [what makes it messy - long functions, no types, hard to test, etc.]

**Requirements:** 
- Clean and modular
- Type-safe
- Tested
- With logging
- [any other specific requirements]
```

## Example Usage

```
Here's messy code → make it clean, modular, type-safe, tested, with logging.

**Current Code:**
```javascript
function processUserData(data) {
    let result = [];
    for(let i = 0; i < data.length; i++) {
        if(data[i].age > 18 && data[i].email.includes('@')) {
            let user = {
                name: data[i].firstName + ' ' + data[i].lastName,
                email: data[i].email,
                isActive: data[i].status === 'active' ? true : false
            };
            result.push(user);
        }
    }
    return result;
}
```

**Language/Framework:** JavaScript/Node.js

**Specific Issues:** 
- No type safety
- Imperative style instead of functional
- No error handling
- No logging
- Hard to test individual parts
- Mixed concerns

**Requirements:**
- Clean and modular
- Type-safe (TypeScript)
- Tested (Jest)
- With logging
- Functional programming style
- Proper error handling
```

## What You'll Get

When using this template, you can expect:

- **Refactored Code**: Clean, readable, and maintainable implementation
- **Type Definitions**: TypeScript interfaces, types, or language-specific type annotations
- **Modular Structure**: Separated concerns with single-responsibility functions/classes
- **Unit Tests**: Comprehensive test coverage for the refactored code
- **Logging Implementation**: Appropriate logging for debugging and monitoring
- **Error Handling**: Proper exception handling and edge case management
- **Documentation**: Comments and documentation for complex logic
- **Best Practices**: Following language and framework conventions

## Tips for Better Results

- **Include the full context**: Show related functions or classes that interact with your code
- **Specify your tech stack**: Mention testing frameworks, type systems, logging libraries you prefer
- **Identify specific pain points**: What makes the code hard to maintain or extend?
- **Mention performance concerns**: If there are specific performance requirements
- **State your team's skill level**: This helps tailor the complexity of the solution
- **Include any constraints**: Legacy system compatibility, coding standards, etc.
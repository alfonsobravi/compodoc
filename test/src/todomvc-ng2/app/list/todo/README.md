# Todo component

This is the core component of the application.

It display the line of one todo task, and APIs for edition & delete

This is an extract of these APIs

```typescript
export class TodoComponent {
    ...
    editTodo(todo: Todo) {
        todo.editing = true;
    }
    ...
}
```

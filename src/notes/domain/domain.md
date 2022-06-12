# Domain

Domain is the rules of our bussines, like internal operations or logic.

Note -> Entity
NoteId -> Value Object
NoteRepository, ej:

```typescript
interface NoteRepository {
    searchAll(): Promise<Array<Note>>;
    save(note: Note): Promise<void>;
}
```

NoteNotFound -> Exception
NoteCreated -> Domain
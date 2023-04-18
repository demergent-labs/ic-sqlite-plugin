# ic-sqlite-plugin

This is an example Azle plugin for the [ICSQlite[(https://github.com/froghub-io/ic-sqlite) project.

We do not plan on maintaining this plugin, it is meant for demonstration purposes only. If you are interested, please fork and maintain this plugin.

## Installation

```bash
npm install https://github.com/demergent-labs/ic-sqlite-plugin
```

## Usage

```typescript
import { $query, $update } from 'azle';
import { ExecuteResult, QueryResult, SQLite } from 'ic-sqlite-plugin';

$update;
export function execute(sql: string): ExecuteResult {
    return SQLite.execute(sql);
}

$query;
export function query(sql: string): QueryResult {
    return SQLite.query(sql);
}

```

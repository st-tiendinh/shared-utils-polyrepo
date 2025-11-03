# Shared Utils Polyrepo

Shared utility functions for common tasks.

## Installation

```bash
npm install @st-tiendinh/shared-utils-polyrepo
```

## Usage

### formatDate

Format dates in short or long format:

```typescript
import { formatDate } from '@st-tiendinh/shared-utils-polyrepo';

// Short format (MM/DD/YYYY)
formatDate(new Date(), 'short'); // "11/03/2025"

// Long format (with weekday)
formatDate(new Date(), 'long'); // "Sunday, November 3, 2025"

// Works with string dates too
formatDate('2025-11-03', 'short'); // "11/03/2025"
```

## API

### `formatDate(date: Date | string, format?: 'short' | 'long'): string`

- **date**: A Date object or date string
- **format**: Optional format type (default: 'short')
  - `'short'`: Returns MM/DD/YYYY format
  - `'long'`: Returns full date with weekday

## License

ISC

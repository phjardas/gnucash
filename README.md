# Access library for GnuCash Ledgers

## Installation

```bash
# with npm
npm i gnucash

# with yarn
yarn add gnucash
```

## Usage

```typescript
import { parseGnucash } from 'gnucash';
import * as fs from 'fs';

(async () => {
  const source = fs.createReadStream('MyGnucashFile.gnucash');
  const gnucash = await parseGnucash(source);
})();
```

## Maintainers

- [Philipp Jardas](https://github.com/phjardas)

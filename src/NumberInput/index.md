## NumberInput

### Demo

```tsx
import React from 'react';
import { NumberInput } from 'qcloud-iot-panel-component';

export default () => (
  <div>
    <NumberInput value={10} step={2} min={0} max={200} templateInfo={{define: {unit: '度'}}}/>
    <NumberInput value={10.1} step={0.2} min={0} max={200} templateInfo={{define: {unit: '度'}}}/>
  </div>
)
```
<API></API>

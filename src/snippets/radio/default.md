---
description:
  zh-CN: "单选框"
  en-US: "Radio"
---

```html
<nz-radio-group [(ngModel)]="$1">
  <label nz-radio nzValue="A">A</label>
  <label *ngFor="let ${3:item} of ${2:list}" nz-radio [nzValue]="$3">{{${3}.text}}</label>
</nz-radio-group>
$0
```

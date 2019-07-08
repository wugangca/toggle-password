# toggle-password
Show and hide password directive with Angular, Bootstrap, and Font Awesome.

See a demo at https://angular-rdaasr.stackblitz.io/

## Usage
- Include <a href="https://getbootstrap.com/"> Bootstrap </a> and <a href="https://fontawesome.com/"> Font Awesome </a> in your Angular project.
- Put the directive code into your Angular project.
- Import the directive module
```ts
// app.module.ts
import { TogglePasswordDirective } from './your/path/to/toggle-password.directive';

...
@NgModule({
  ...
  declarations: [
    ...
    TogglePasswordDirective
  ],
  ...
})
```
- Use the directive **appTogglePassword** in any "input" element
```html
<div class="form-group">
  <label for="password">Password</label>
  <input type="password" class="form-control" appTogglePassword/>
</div>
```

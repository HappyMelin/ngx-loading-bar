## Quick Start

#### 1. Install @ngx-loading-bar/http
```bash
  npm install @ngx-loading-bar/http --save
```

#### 2. Import the `LoadingBarHttpModule`:

```ts
import { NgModule } from '@angular/core';
import { BrowserModule } from '@angular/platform-browser';
import { HttpModule } from '@angular/http';
import { LoadingBarHttpModule } from '@ngx-loading-bar/http';
import { AppComponent } from './app';

@NgModule({
  imports: [
    BrowserModule,
    HttpModule,
    LoadingBarHttpModule,
  ],
  declarations: [ AppComponent ],
  bootstrap: [ AppComponent ],
})
export class AppModule {
}

```

#### 3. Include `ngx-loading-bar` in your app component:

```ts
import { Component } from '@angular/core';

@Component({
  selector: 'app',
  template: `
    ...
    <ngx-loading-bar></ngx-loading-bar>
  `,
})
export class AppComponent {}

```

#### 4. include the supplied CSS file (or create your own).
  - [loading-bar.css](loading-bar.css)


Based on https://github.com/sir-valentin/Angular2LoadingBar.git

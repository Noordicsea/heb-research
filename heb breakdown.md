## HEB's website breakdown

Search Bar:

```html
<input class="SearchBar_searchInput__qc1pz" id="search-input" data-qe-id="searchBar" name="q" aria-label="Search H E B.com" autocomplete="off" autocorrect="off" autocapitalize="off" type="search" role="combobox" placeholder="Search" aria-autocomplete="list" maxlength="500" aria-expanded="false" value="">
```

Cart:
```url
https://www.heb.com/cart
```

Empty Cart:
```url
https://www.heb.com/cart


```

## login

navigate:
https://www.heb.com/

### log in:
```html
<a href="/my-account/login" class="Link_link__LFJGw sc-8fe3a248-2 bGZKTa" data-component="link">log in</a>
```

### Login field:
```html<input autocomplete="email" autocapitalize="none" autocorrect="off" spellcheck="false" class="form-control bg-transparent rounded-none read-only:bg-lighter-gray read-only:text-dark-gray " type="email" id="email-input" placeholder="Email" name="email">
```

### Password field:
```html
<input autocomplete="current-password" autocapitalize="none" spellcheck="false" class="form-control bg-transparent rounded-none read-only:bg-lighter-gray read-only:text-dark-gray " type="password" id="password-input" placeholder="Password" name="password">
```


There might be a one time code that is required:
### One-time-code page:
```url
https://accounts.heb.com/interaction/[INTERACTION-ID]/challenge
```
note: This seems to be a unique moment where the URL ends in '/challenge' We might be able to use this to identify this interaction later.

### Code box entry:
```html
<input type="tel" name="code_input_1" aria-label="code_input_1">
<input type="tel" name="code_input_2" aria-label="code_input_2">
<input type="tel" name="code_input_3" aria-label="code_input_3">
<input type="tel" name="code_input_4" aria-label="code_input_4">
<input type="tel" name="code_input_5" aria-label="code_input_5">
<input type="tel" name="code_input_6" aria-label="code_input_6">
```
Note: You can promt the user for this code with an input field and just contenue on.

### Verify Code Button:
```html
<button class="focus:shadow-blue-border w-full rounded-3xl font-extrabold px-2 py-2.5 disabled:opacity-30 text-white bg-dark-gray hover:bg-light-gray " type="submit" aria-disabled="false">Verify</button>
```


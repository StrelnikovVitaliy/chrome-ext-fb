
Clone the repo:

```
git clone git@github.com:StrelnikovVitaliy/chrome-ext-fb.git name-of-your-project
```

Set git to track your own repository instead of this one:

```
git remote set-url --delete origin git@github.com:StrelnikovVitaliy/chrome-ext-fb.git # Remove old origin
git remote set-url --add origin [YOUR REPO URL] # Add new origin
```

Install dependencies:

```
yarn install # or npm install
```

## Usage

To run a development server that will watch for file changes and rebuild the scripts, run:

```
yarn start
```

To just build the files without the development server:

```
yarn build
```

Add extension to the Chrome `chrome://extensions/` in `dev mode`
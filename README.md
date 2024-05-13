## Instructions

#### 1. Create a project folder
```sh
mkdir ts-project
```

#### 2. Initiate a JS project
```sh
npm init --y
```

#### 3. Create TS config file
```sh
tsc --init
```

#### 4. Create src and dist (distribution) directories
```sh
mkdir src dist
```

#### 5. Go to the TS config file and change configuration to dir for genarated js file
```sh
outDir = "./dist"
```

#### 6. Run the TS watchman
```sh
tsc -w
```
#### 7. Install the live server extension for run the `index.html` file as a server
# Metaverse
Modern Next 13 Website With Framer Motion &amp; Tailwind CSS

<h2>To view the prototype at Figma for this website check out the following link: </h2>

<a href="https://www.figma.com/proto/FcrtNOBixgkqtqUZulxtu4/Modern-UI%2FUX-Framer-Motion?type=design&node-id=1-4&t=8xddDqzESEwpsUdI-1&scaling=min-zoom&page-id=0%3A1&mode=design">link to visit</a>

<!-- <p>To get started, you can download the ZIP file by clicking the following link:</p>
<a href="path/to/your/zip/file.zip" download>Download ZIP File</a>
-->

<h2>How to get started</h2>
<p> the first bug i faced while setting up the project was :

:~/Desktop/metaverses$ npm run dev

> metaverse13@0.1.0 dev
> next dev

/home/----/Desktop/metaverses/node_modules/next/dist/cli/next-dev.js:299
                    showAll: args["--show-all"] ?? false,
                                                 ^

SyntaxError: Unexpected token '?'
    at wrapSafe (internal/modules/cjs/loader.js:915:16)
    at Module._compile (internal/modules/cjs/loader.js:963:27)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1027:10)
    at Module.load (internal/modules/cjs/loader.js:863:32)
    at Function.Module._load (internal/modules/cjs/loader.js:708:14)
    at Module.require (internal/modules/cjs/loader.js:887:19)
    at require (internal/modules/cjs/helpers.js:74:18)
    at Object.dev (/home/anagha/Desktop/metaverses/node_modules/next/dist/lib/commands.js:10:30)
    at Object.<anonymous> (/home/anagha/Desktop/metaverses/node_modules/next/dist/bin/next:141:28)
    at Module._compile (internal/modules/cjs/loader.js:999:30)

</p>
<br>
<p>nullish coalescing operator is the cause of this error. it suggests that the system has Node.js with a version that does not support this operator.to resolve this the following commands must be executed in the terminal in order.</p>
<h4>to update nodejs follow the following steps:</h4>
<h4>1.Check your current Node.js version by running the following command: </h4>
<h5>node -v</h5>
<h4>2.If your Node.js version is older than 14.0.0, you can use Node Version Manager (NVM) to install and manage multiple Node.js versions on your system. If you don't have NVM installed, you can install it by running the following command:
</h4>
<h5> curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash</h5>
<h4>3.Install the latest LTS (Long-Term Support) version of Node.js using NVM: 
</h4>
<h5>nvm install --lts</h5>
<h4>3.Set the newly installed Node.js version as the default version:
</h4>
<img src=Screenshot from 2023-07-17 13-19-59.png" alt="npm run dev successful run" width="300" height="200">

<h5>nvm use --lts</h5>
<h4>4.Verify that your Node.js version has been updated by running: </h4>
<h5>node -v</h5>
<p> this should fix your issues with this!</p>

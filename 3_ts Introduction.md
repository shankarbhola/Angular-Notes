TypeScript
-

**What is TypeScript?**
- It is an open source, cross platform language introduced by Microsoft.
- Developed by "Anders Hejlberg". [C#]
- It supports complete OOP.
- It is strictly typed.
- It is strongly typed. [Duck Typing]
- It is used to build large scale apps.
- TypeScript is built with TypeScript.
- Supports Low Level features
- Directly interact with Hardware sevices.
- Faster

**Note:**  Browser can't understand TypeScript, It trans compiles type script into JavaScript.

Developer => TypeScript => Translated into JavaScript => Browser


Type Script Architecture
-

1. TypeScript Core Compiler
    - It identifies the syntactical errors in program.
    - It reports the errors
    - It handles all compilation process by using
        - program.ts
        - checker.ts
        - parser.ts
        - scanner.ts
        - emitter.ts etc..

2. Standalone TS compiler
    - It translates a TypeScript program into JavaScript program

   program.ts => core compiler => standalone compiler => program.js


3. Language Service
    - Language comprises of a factory
    - Factory is a set of related type of functions and values
    - Service is a set of related type of factories.
    - Application uses a service.
    - Complier uses a service to verify the keywords, functions, syntax etc.


4. TsServer [TypeScript Server]
   - Server role is hosting, handling request and response.
   - TypeScript programs are loaded, complied, transcomplied in TS Server.
   - It handles the request, process the request and generates a response customized for every request.


5. VS Shim  [Visual Studio Shim]
    - It is responsible for making the TypeScript program platform neutral.
    - TypeScript program can run on any OS.

UnManaged Code	=> shim =>  Managed Code
[Platform dependent]		   [Platform Independent]
			
		
6. Managed Language Service
    - It comprises of services which are platform independent.


Setup Environment for TypeScript
-

1. Download and Install "Node.js" on your PC.

    [ for a package manager NPM ]

	Install Node JS  12+,  16+
	          NPM  6+ , 8+

   C:\> node  -v
   C:\> npm  -v

2. Download and Install TypeScript on your PC.

        C:\>npm install  -g  typescript

        C:\> tsc  -v

3. Download and Install "Visual Studio Code" editor
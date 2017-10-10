# Typescript
## Basic Types
-Boolean
-string
-number
-array
-tuple
-enum
-any
-void
-null /undefined
-Type assertions
-let


### 1.Boolean
         Ex: 'let' expr:boolean=true
### 2.String
         Ex: 'let' expr:string='muthumani'
### 3.Number
         Ex: let expr:number=6  --decimal
         Ex: let expr:number=0xf00d  --hex
         Ex: let expr:number=0b1010  --binary
         Ex: let expr:number=0o744  --octal
         
### 4.Array:
  Ist way  :
        Ex: let expr:number[]=[1,2,3,4]      --------- number array
        Ex: let expr:number[]=['mani','raja','bala','mallika']      --------- String array
  II nd Way:
        Ex: let expr:Array<number>=[1,2,3,4]
        Ex: let expr:Array<string>=['mani','raja','bala','mallika']
         
### 5.Tuple:
      Tuple types allow you to express an array where the type of a fixed number of elements is known, but need not be the same.
      // Declare a tuple type
      let x: [string, number];
      // Initialize it
      x = ["hello", 10]; // OK
### 6.enum

      enum 

# Jasmine Matchers Snippets

In order to use the snippets, just enter the shortcode and press <kbd>Tab</kbd> (or whatever you have set as completion key) to use the snippets.

Included are all snippets listed below. $1, $2, etc. show the position where the caret will appear whenever you press the tab key inside the snippet.

These snippets are intended to be used alongside [Jasmine Matchers](https://github.com/JamieMason/Jasmine-Matchers) to make development a little easier.


## toBe

`tb` -> `expect(${1:instance}).toBe(${2:instance});`

## toBeArray

`tba` -> `expect(${1:array}).toBeArray();`

## toBeAfter

`tba` -> `expect(${1:date}).toBeAfter(${2:date});`

## toBeArrayOfBooleans

`tbaob` -> `expect(${1:array}).toBeArrayOfBooleans();`

## toBeArrayOfNumbers

`tbaon` -> `expect(${1:array}).toBeArrayOfNumbers();`

## toBeArrayOfObjects

`tbaoo` -> `expect(${1:array}).toBeArrayOfObjects();`

## toBeArrayOfSize

`tbaos` -> `expect(${1:array}).toBeArrayOfSize(${2:size});`

## toBeArrayOfStrings

`tbaos` -> `expect(${1:array}).toBeArrayOfStrings();`

## toBeBoolean

`tbb` -> `expect(${1:boolean}).toBeBoolean();`

## toBeBefore

`tbb` -> `expect(${1:date}).toBeBefore(${2:date});`

## toBeCalculable

`tbc` -> `expect(${1:numberOrString}).toBeCalculable();`

## toBeDate

`tbd` -> `expect(${1:date}).toBeDate();`

## toBeDefined

`tbd` -> `expect(${1:mixed}).toBeDefined();`

## toBeDocument

`tbd` -> `expect(${1:object}).toBeDocument();`

## toBeEmptyArray

`tbea` -> `expect(${1:array}).toBeEmptyArray();`

## toBeEvenNumber

`tben` -> `expect(${1:number}).toBeEvenNumber();`

## toBeEmptyString

`tbes` -> `expect(${1:string}).toBeEmptyString();`

## toBeFalse

`tbf` -> `expect(${1:boolean}).toBeFalse();`

## toBeFalsy

`tbf` -> `expect(${1:mixed}).toBeFalsy();`

## toBeFunction

`tbf` -> `expect(${1:object}).toBeFunction();`

## toBeGreaterThan

`tbgt` -> `expect(${1:number}).toBeGreaterThan(${2:number});`

## toBeHtmlCommentNode

`tbhcn` -> `expect(${1:element}).toBeHtmlCommentNode();`

## toBeHtmlNode

`tbhn` -> `expect(${1:element}).toBeHtmlNode();`

## toBeHtmlString

`tbhs` -> `expect(${1:string}).toBeHtmlString();`

## toBeHtmlTextNode

`tbhtn` -> `expect(${1:element}).toBeHtmlTextNode();`

## toBeIso8601

`tbi8601` -> `expect(${1:string}).toBeIso8601();`

## toBeJsonString

`tbjs` -> `expect(${1:string}).toBeJsonString();`

## toBeLessThan

`tblt` -> `expect(${1:number}).toBeLessThan(${2:number});`

## toBeLongerThan

`tblt` -> `expect(${1:string}).toBeLongerThan(${2:other});`

## toBeNull

`tbn` -> `expect(${1:mixed}).toBeNull();`

## toBeNumber

`tbn` -> `expect(${1:number}).toBeNumber();`

## toBeNonEmptyArray

`tbnea` -> `expect(${1:array}).toBeNonEmptyArray();`

## toBeNonEmptyString

`tbnes` -> `expect(${1:string}).toBeNonEmptyString();`

## toBeObject

`tbo` -> `expect(${1:object}).toBeObject();`

## toBeOddNumber

`tbon` -> `expect(${1:number}).toBeOddNumber();`

## toBeString

`tbs` -> `expect(${1:string}).toBeString();`

## toBeSameLengthAs

`tbsla` -> `expect(${1:string}).toBeSameLengthAs(${2:other});`

## toBeShorterThan

`tbst` -> `expect(${1:string}).toBeShorterThan(${2:other});`

## toBeTrue

`tbt` -> `expect(${1:boolean}).toBeTrue();`

## toBeTruthy

`tbt` -> `expect(${1:mixed}).toBeTruthy();`

## toBeUndefined

`tbu` -> `expect(${1:mixed}).toBeUndefined();`

## toBeWindow

`tbw` -> `expect(${1:object}).toBeWindow();`

## toBeWhitespace

`tbw` -> `expect(${1:string}).toBeWhitespace();`

## toBeWholeNumber

`tbwn` -> `expect(${1:number}).toBeWholeNumber();`

## toBeWithinRange

`tbwr` -> `expect(${1:number}).toBeWithinRange(${2:floor}, ${3:ceiling});`

## toContain

`tc` -> `expect(${1:array or string}).toContain(${2:member or substring});`

## toEqual

`te` -> `expect(${1:mixed}).toEqual(${2:mixed});`

## toEndWith

`tew` -> `expect(${1:string}).toEndWith(${2:expected});`

## toHaveArray

`tha` -> `expect(${1:object}).toHaveArray(${2:memberName});`

## toHaveArrayOfBooleans

`thaob` -> `expect(${1:object}).toHaveArrayOfBooleans(${2:memberName});`

## toHaveArrayOfNumbers

`thaon` -> `expect(${1:object}).toHaveArrayOfNumbers(${2:memberName});`

## toHaveArrayOfObjects

`thaoo` -> `expect(${1:object}).toHaveArrayOfObjects(${2:memberName});`

## toHaveArrayOfSize

`thaos` -> `expect(${1:object}).toHaveArrayOfSize(memberName, ${2:size});`

## toHaveArrayOfStrings

`thaos` -> `expect(${1:object}).toHaveArrayOfStrings(${2:memberName});`

## toHaveEmptyArray

`thea` -> `expect(${1:object}).toHaveEmptyArray(${2:memberName});`

## toHaveNonEmptyArray

`thnea` -> `expect(${1:object}).toHaveNonEmptyArray(${2:memberName});`

## toImplement

`ti` -> `expect(${1:object}).toImplement(${2:api});`

## toMatch

`tm` -> `expect(${1:mixed}).toMatch(${2:pattern});`

## toStartWith

`tsw` -> `expect(${1:string}).toStartWith(${2:expected});`

## toThrow

`tt` -> `expect(${1:fn}).toThrow(${2:error});`

## toThrowAnyError

`ttae` -> `expect(${1:fn}).toThrowAnyError();`

## toThrowErrorOfType

`tteot` -> `expect(${1:fn}).toThrowErrorOfType(${2:string});`

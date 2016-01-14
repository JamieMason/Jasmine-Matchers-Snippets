# Jasmine Matchers Snippets

Snippets to ease development with [Jasmine Matchers](https://github.com/JamieMason/Jasmine-Matchers).

In order to use the snippets, just enter the shortcode and press <kbd>Tab</kbd>. 

Each snippet should be easy to remember as they follow the first and capital letters of each matcher, such as <kbd>t</kbd>`o`<kbd>h</kbd>`ave`<kbd>a</kbd>`rray`<kbd>o</kbd>`f`<kbd>b</kbd>`ooleans`.

Put an <kbd>n</kbd> at the beginning for `.not` cases; 

+ <kbd>t</kbd><kbd>b</kbd> creates `expect(instance).toBe(instance)`
+ <kbd>n</kbd><kbd>t</kbd><kbd>b</kbd> creates `expect(instance).not.toBe(instance)`

`$1`, `$2` etc shows the position where the caret will appear after you've inserted a snippet. Pressing <kbd>Tab</kbd> again will move the caret to the next `$n`.

<kbd>a</kbd><kbd>f</kbd>
```javascript
afterEach(function() {

});
```

<kbd>b</kbd><kbd>e</kbd>
```javascript
beforeEach(function() {

});
```

<kbd>d</kbd><kbd>e</kbd><kbd>s</kbd>
```javascript
describe('when x', function() {

});
```

<kbd>i</kbd><kbd>t</kbd>
```javascript
it('should x', function() {

});
```

<kbd>j</kbd><kbd>a</kbd>
```javascript
jasmine.createSpy('name');
```

<kbd>t</kbd><kbd>b</kbd>
```javascript
expect(instance).toBe(instance);
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd>
```javascript
expect(date).toBeAfter(date);
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd>
```javascript
expect(array).toBeArray();
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd><kbd>o</kbd><kbd>b</kbd>
```javascript
expect(array).toBeArrayOfBooleans();
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd><kbd>o</kbd><kbd>n</kbd>
```javascript
expect(array).toBeArrayOfNumbers();
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd><kbd>o</kbd><kbd>o</kbd>
```javascript
expect(array).toBeArrayOfObjects();
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd><kbd>o</kbd><kbd>s</kbd>
```javascript
expect(array).toBeArrayOfSize(size);
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd><kbd>o</kbd><kbd>s</kbd>
```javascript
expect(array).toBeArrayOfStrings();
```

<kbd>t</kbd><kbd>b</kbd><kbd>b</kbd>
```javascript
expect(date).toBeBefore(date);
```

<kbd>t</kbd><kbd>b</kbd><kbd>b</kbd>
```javascript
expect(boolean).toBeBoolean();
```

<kbd>t</kbd><kbd>b</kbd><kbd>c</kbd>
```javascript
expect(numberOrString).toBeCalculable();
```

<kbd>t</kbd><kbd>b</kbd><kbd>d</kbd>
```javascript
expect(date).toBeDate();
```

<kbd>t</kbd><kbd>b</kbd><kbd>d</kbd>
```javascript
expect(mixed).toBeDefined();
```

<kbd>t</kbd><kbd>b</kbd><kbd>d</kbd>
```javascript
expect(object).toBeDocument();
```

<kbd>t</kbd><kbd>b</kbd><kbd>e</kbd><kbd>a</kbd>
```javascript
expect(array).toBeEmptyArray();
```

<kbd>t</kbd><kbd>b</kbd><kbd>e</kbd><kbd>s</kbd>
```javascript
expect(string).toBeEmptyString();
```

<kbd>t</kbd><kbd>b</kbd><kbd>e</kbd><kbd>n</kbd>
```javascript
expect(number).toBeEvenNumber();
```

<kbd>t</kbd><kbd>b</kbd><kbd>f</kbd>
```javascript
expect(boolean).toBeFalse();
```

<kbd>t</kbd><kbd>b</kbd><kbd>f</kbd>
```javascript
expect(mixed).toBeFalsy();
```

<kbd>t</kbd><kbd>b</kbd><kbd>f</kbd>
```javascript
expect(object).toBeFunction();
```

<kbd>t</kbd><kbd>b</kbd><kbd>g</kbd><kbd>t</kbd>
```javascript
expect(number).toBeGreaterThan(number);
```

<kbd>t</kbd><kbd>b</kbd><kbd>h</kbd><kbd>c</kbd><kbd>n</kbd>
```javascript
expect(element).toBeHtmlCommentNode();
```

<kbd>t</kbd><kbd>b</kbd><kbd>h</kbd><kbd>n</kbd>
```javascript
expect(element).toBeHtmlNode();
```

<kbd>t</kbd><kbd>b</kbd><kbd>h</kbd><kbd>s</kbd>
```javascript
expect(string).toBeHtmlString();
```

<kbd>t</kbd><kbd>b</kbd><kbd>h</kbd><kbd>t</kbd><kbd>n</kbd>
```javascript
expect(element).toBeHtmlTextNode();
```

<kbd>t</kbd><kbd>b</kbd><kbd>i</kbd><kbd>8</kbd><kbd>6</kbd><kbd>0</kbd><kbd>1</kbd>
```javascript
expect(string).toBeIso8601();
```

<kbd>t</kbd><kbd>b</kbd><kbd>j</kbd><kbd>s</kbd>
```javascript
expect(string).toBeJsonString();
```

<kbd>t</kbd><kbd>b</kbd><kbd>l</kbd><kbd>t</kbd>
```javascript
expect(number).toBeLessThan(number);
```

<kbd>t</kbd><kbd>b</kbd><kbd>l</kbd><kbd>t</kbd>
```javascript
expect(string).toBeLongerThan(other);
```

<kbd>t</kbd><kbd>b</kbd><kbd>n</kbd><kbd>e</kbd><kbd>a</kbd>
```javascript
expect(array).toBeNonEmptyArray();
```

<kbd>t</kbd><kbd>b</kbd><kbd>n</kbd><kbd>e</kbd><kbd>s</kbd>
```javascript
expect(string).toBeNonEmptyString();
```

<kbd>t</kbd><kbd>b</kbd><kbd>n</kbd>
```javascript
expect(mixed).toBeNull();
```

<kbd>t</kbd><kbd>b</kbd><kbd>n</kbd>
```javascript
expect(number).toBeNumber();
```

<kbd>t</kbd><kbd>b</kbd><kbd>o</kbd>
```javascript
expect(object).toBeObject();
```

<kbd>t</kbd><kbd>b</kbd><kbd>o</kbd><kbd>n</kbd>
```javascript
expect(number).toBeOddNumber();
```

<kbd>t</kbd><kbd>b</kbd><kbd>s</kbd><kbd>l</kbd><kbd>a</kbd>
```javascript
expect(string).toBeSameLengthAs(other);
```

<kbd>t</kbd><kbd>b</kbd><kbd>s</kbd><kbd>t</kbd>
```javascript
expect(string).toBeShorterThan(other);
```

<kbd>t</kbd><kbd>b</kbd><kbd>s</kbd>
```javascript
expect(string).toBeString();
```

<kbd>t</kbd><kbd>b</kbd><kbd>t</kbd>
```javascript
expect(boolean).toBeTrue();
```

<kbd>t</kbd><kbd>b</kbd><kbd>t</kbd>
```javascript
expect(mixed).toBeTruthy();
```

<kbd>t</kbd><kbd>b</kbd><kbd>u</kbd>
```javascript
expect(mixed).toBeUndefined();
```

<kbd>t</kbd><kbd>b</kbd><kbd>w</kbd>
```javascript
expect(string).toBeWhitespace();
```

<kbd>t</kbd><kbd>b</kbd><kbd>w</kbd><kbd>n</kbd>
```javascript
expect(number).toBeWholeNumber();
```

<kbd>t</kbd><kbd>b</kbd><kbd>w</kbd>
```javascript
expect(object).toBeWindow();
```

<kbd>t</kbd><kbd>b</kbd><kbd>w</kbd><kbd>r</kbd>
```javascript
expect(number).toBeWithinRange(floor, ceiling);
```

<kbd>t</kbd><kbd>c</kbd>
```javascript
expect(arrayor string}).toContain(memberor substring});
```

<kbd>t</kbd><kbd>e</kbd><kbd>w</kbd>
```javascript
expect(string).toEndWith(expected);
```

<kbd>t</kbd><kbd>e</kbd>
```javascript
expect(mixed).toEqual(mixed);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd>
```javascript
expect(object).toHaveArray(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd><kbd>o</kbd><kbd>b</kbd>
```javascript
expect(object).toHaveArrayOfBooleans(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd><kbd>o</kbd><kbd>n</kbd>
```javascript
expect(object).toHaveArrayOfNumbers(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd><kbd>o</kbd><kbd>o</kbd>
```javascript
expect(object).toHaveArrayOfObjects(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd><kbd>o</kbd><kbd>s</kbd>
```javascript
expect(object).toHaveArrayOfSize(memberName, size);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd><kbd>o</kbd><kbd>s</kbd>
```javascript
expect(object).toHaveArrayOfStrings(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>e</kbd><kbd>a</kbd>
```javascript
expect(object).toHaveEmptyArray(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>n</kbd><kbd>e</kbd><kbd>a</kbd>
```javascript
expect(object).toHaveNonEmptyArray(memberName);
```

<kbd>t</kbd><kbd>i</kbd>
```javascript
expect(object).toImplement(api);
```

<kbd>t</kbd><kbd>m</kbd>
```javascript
expect(mixed).toMatch(pattern);
```

<kbd>t</kbd><kbd>s</kbd><kbd>w</kbd>
```javascript
expect(string).toStartWith(expected);
```

<kbd>t</kbd><kbd>t</kbd>
```javascript
expect(fn).toThrow(error);
```

<kbd>t</kbd><kbd>t</kbd><kbd>a</kbd><kbd>e</kbd>
```javascript
expect(fn).toThrowAnyError();
```

<kbd>t</kbd><kbd>t</kbd><kbd>e</kbd><kbd>o</kbd><kbd>t</kbd>
```javascript
expect(fn).toThrowErrorOfType(string);
```

<kbd>a</kbd><kbd>c</kbd><kbd>f</kbd>
```javascript
spyOn(object, 'methodName').and.callFake();
```

<kbd>a</kbd><kbd>c</kbd><kbd>t</kbd>
```javascript
spyOn(object, 'methodName').and.callThrough();
```

<kbd>a</kbd><kbd>r</kbd><kbd>v</kbd>
```javascript
spyOn(object, 'methodName').and.returnValue(value);
```

<kbd>a</kbd><kbd>t</kbd><kbd>e</kbd>
```javascript
spyOn(object, 'methodName').and.throwError('message');
```

<kbd>t</kbd><kbd>b</kbd>
```javascript
expect(instance).toBe(instance);
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd>
```javascript
expect(date).toBeAfter(date);
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd>
```javascript
expect(array).toBeArray();
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd><kbd>o</kbd><kbd>b</kbd>
```javascript
expect(array).toBeArrayOfBooleans();
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd><kbd>o</kbd><kbd>n</kbd>
```javascript
expect(array).toBeArrayOfNumbers();
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd><kbd>o</kbd><kbd>o</kbd>
```javascript
expect(array).toBeArrayOfObjects();
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd><kbd>o</kbd><kbd>s</kbd>
```javascript
expect(array).toBeArrayOfSize(size);
```

<kbd>t</kbd><kbd>b</kbd><kbd>a</kbd><kbd>o</kbd><kbd>s</kbd>
```javascript
expect(array).toBeArrayOfStrings();
```

<kbd>t</kbd><kbd>b</kbd><kbd>b</kbd>
```javascript
expect(date).toBeBefore(date);
```

<kbd>t</kbd><kbd>b</kbd><kbd>b</kbd>
```javascript
expect(boolean).toBeBoolean();
```

<kbd>t</kbd><kbd>b</kbd><kbd>c</kbd>
```javascript
expect(numberOrString).toBeCalculable();
```

<kbd>t</kbd><kbd>b</kbd><kbd>d</kbd>
```javascript
expect(date).toBeDate();
```

<kbd>t</kbd><kbd>b</kbd><kbd>d</kbd>
```javascript
expect(mixed).toBeDefined();
```

<kbd>t</kbd><kbd>b</kbd><kbd>d</kbd>
```javascript
expect(object).toBeDocument();
```

<kbd>t</kbd><kbd>b</kbd><kbd>e</kbd><kbd>a</kbd>
```javascript
expect(array).toBeEmptyArray();
```

<kbd>t</kbd><kbd>b</kbd><kbd>e</kbd><kbd>s</kbd>
```javascript
expect(string).toBeEmptyString();
```

<kbd>t</kbd><kbd>b</kbd><kbd>e</kbd><kbd>n</kbd>
```javascript
expect(number).toBeEvenNumber();
```

<kbd>t</kbd><kbd>b</kbd><kbd>f</kbd>
```javascript
expect(boolean).toBeFalse();
```

<kbd>t</kbd><kbd>b</kbd><kbd>f</kbd>
```javascript
expect(mixed).toBeFalsy();
```

<kbd>t</kbd><kbd>b</kbd><kbd>f</kbd>
```javascript
expect(object).toBeFunction();
```

<kbd>t</kbd><kbd>b</kbd><kbd>g</kbd><kbd>t</kbd>
```javascript
expect(number).toBeGreaterThan(number);
```

<kbd>t</kbd><kbd>b</kbd><kbd>h</kbd><kbd>c</kbd><kbd>n</kbd>
```javascript
expect(element).toBeHtmlCommentNode();
```

<kbd>t</kbd><kbd>b</kbd><kbd>h</kbd><kbd>n</kbd>
```javascript
expect(element).toBeHtmlNode();
```

<kbd>t</kbd><kbd>b</kbd><kbd>h</kbd><kbd>s</kbd>
```javascript
expect(string).toBeHtmlString();
```

<kbd>t</kbd><kbd>b</kbd><kbd>h</kbd><kbd>t</kbd><kbd>n</kbd>
```javascript
expect(element).toBeHtmlTextNode();
```

<kbd>t</kbd><kbd>b</kbd><kbd>i</kbd><kbd>8</kbd><kbd>6</kbd><kbd>0</kbd><kbd>1</kbd>
```javascript
expect(string).toBeIso8601();
```

<kbd>t</kbd><kbd>b</kbd><kbd>j</kbd><kbd>s</kbd>
```javascript
expect(string).toBeJsonString();
```

<kbd>t</kbd><kbd>b</kbd><kbd>l</kbd><kbd>t</kbd>
```javascript
expect(number).toBeLessThan(number);
```

<kbd>t</kbd><kbd>b</kbd><kbd>l</kbd><kbd>t</kbd>
```javascript
expect(string).toBeLongerThan(other);
```

<kbd>t</kbd><kbd>b</kbd><kbd>n</kbd><kbd>e</kbd><kbd>a</kbd>
```javascript
expect(array).toBeNonEmptyArray();
```

<kbd>t</kbd><kbd>b</kbd><kbd>n</kbd><kbd>e</kbd><kbd>s</kbd>
```javascript
expect(string).toBeNonEmptyString();
```

<kbd>t</kbd><kbd>b</kbd><kbd>n</kbd>
```javascript
expect(mixed).toBeNull();
```

<kbd>t</kbd><kbd>b</kbd><kbd>n</kbd>
```javascript
expect(number).toBeNumber();
```

<kbd>t</kbd><kbd>b</kbd><kbd>o</kbd>
```javascript
expect(object).toBeObject();
```

<kbd>t</kbd><kbd>b</kbd><kbd>o</kbd><kbd>n</kbd>
```javascript
expect(number).toBeOddNumber();
```

<kbd>t</kbd><kbd>b</kbd><kbd>s</kbd><kbd>l</kbd><kbd>a</kbd>
```javascript
expect(string).toBeSameLengthAs(other);
```

<kbd>t</kbd><kbd>b</kbd><kbd>s</kbd><kbd>t</kbd>
```javascript
expect(string).toBeShorterThan(other);
```

<kbd>t</kbd><kbd>b</kbd><kbd>s</kbd>
```javascript
expect(string).toBeString();
```

<kbd>t</kbd><kbd>b</kbd><kbd>t</kbd>
```javascript
expect(boolean).toBeTrue();
```

<kbd>t</kbd><kbd>b</kbd><kbd>t</kbd>
```javascript
expect(mixed).toBeTruthy();
```

<kbd>t</kbd><kbd>b</kbd><kbd>u</kbd>
```javascript
expect(mixed).toBeUndefined();
```

<kbd>t</kbd><kbd>b</kbd><kbd>w</kbd>
```javascript
expect(string).toBeWhitespace();
```

<kbd>t</kbd><kbd>b</kbd><kbd>w</kbd><kbd>n</kbd>
```javascript
expect(number).toBeWholeNumber();
```

<kbd>t</kbd><kbd>b</kbd><kbd>w</kbd>
```javascript
expect(object).toBeWindow();
```

<kbd>t</kbd><kbd>b</kbd><kbd>w</kbd><kbd>r</kbd>
```javascript
expect(number).toBeWithinRange(floor, ceiling);
```

<kbd>t</kbd><kbd>c</kbd>
```javascript
expect(arrayor string}).toContain(memberor substring});
```

<kbd>t</kbd><kbd>e</kbd><kbd>w</kbd>
```javascript
expect(string).toEndWith(expected);
```

<kbd>t</kbd><kbd>e</kbd>
```javascript
expect(mixed).toEqual(mixed);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd>
```javascript
expect(object).toHaveArray(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd><kbd>o</kbd><kbd>b</kbd>
```javascript
expect(object).toHaveArrayOfBooleans(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd><kbd>o</kbd><kbd>n</kbd>
```javascript
expect(object).toHaveArrayOfNumbers(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd><kbd>o</kbd><kbd>o</kbd>
```javascript
expect(object).toHaveArrayOfObjects(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd><kbd>o</kbd><kbd>s</kbd>
```javascript
expect(object).toHaveArrayOfSize(memberName, size);
```

<kbd>t</kbd><kbd>h</kbd><kbd>a</kbd><kbd>o</kbd><kbd>s</kbd>
```javascript
expect(object).toHaveArrayOfStrings(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>b</kbd><kbd>c</kbd>
```javascript
expect(method).toHaveBeenCalled();
```

<kbd>t</kbd><kbd>h</kbd><kbd>b</kbd><kbd>c</kbd><kbd>w</kbd>
```javascript
expect(method).toHaveBeenCalledWith(value);
```

<kbd>t</kbd><kbd>h</kbd><kbd>e</kbd><kbd>a</kbd>
```javascript
expect(object).toHaveEmptyArray(memberName);
```

<kbd>t</kbd><kbd>h</kbd><kbd>n</kbd><kbd>e</kbd><kbd>a</kbd>
```javascript
expect(object).toHaveNonEmptyArray(memberName);
```

<kbd>t</kbd><kbd>i</kbd>
```javascript
expect(object).toImplement(api);
```

<kbd>t</kbd><kbd>m</kbd>
```javascript
expect(mixed).toMatch(pattern);
```

<kbd>t</kbd><kbd>s</kbd><kbd>w</kbd>
```javascript
expect(string).toStartWith(expected);
```

<kbd>t</kbd><kbd>t</kbd>
```javascript
expect(fn).toThrow(error);
```

<kbd>t</kbd><kbd>t</kbd><kbd>a</kbd><kbd>e</kbd>
```javascript
expect(fn).toThrowAnyError();
```

<kbd>t</kbd><kbd>t</kbd><kbd>e</kbd><kbd>o</kbd><kbd>t</kbd>
```javascript
expect(fn).toThrowErrorOfType(string);
```

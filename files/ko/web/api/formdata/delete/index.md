---
title: FormData.delete()
slug: Web/API/FormData/delete
page-type: web-api-instance-method
browser-compat: api.FormData.delete
translation_of: Web/API/FormData/delete
---
{{APIRef("XMLHttpRequest")}}

{{domxref("FormData")}} 인터페이스의 **`delete()`** 메서드는 `FormData` 객체에서 key와 그 값에 해당하는 것을 지웁니다.

> **참고:** 이 메서드는 [Web Worker](/ko/docs/Web/API/Web_Workers_API)에서 사용할 수 있습니다.

## Syntax

```js
formData.delete(name);
```

### Parameters

- `name`
  - : 삭제할 key의 이름 입니다.

### Returns

Void.

## Example

다음 코드를 따라 빈 `FormData` 객체를 만들고, form의 key/value 쌍을 미리 채웁니다:

```js
var formData = new FormData(myForm);
```

`delete()`를 사용하여 키와 값을 삭제할 수 있습니다:

```js
formData.delete('username');
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{domxref("XMLHTTPRequest")}}
- [Using XMLHttpRequest](/en-US/docs/DOM/XMLHttpRequest/Using_XMLHttpRequest "Using XMLHttpRequest")
- [Using FormData objects](/en-US/docs/DOM/XMLHttpRequest/FormData/Using_FormData_Objects "DOM/XMLHttpRequest/FormData/Using_FormData_objects")
- {{HTMLElement("Form")}}

#javascript ���������
```javascript
function Aaa() {}
    //    Aaa.prototype.constructor = Aaa;    //�����Զ����ɴ˾仰
    var a = new Aaa();
    console.log(a.constructor.prototype === Aaa.prototype);
    console.log(a.__proto__ === Aaa.prototype);
    console.log(a.constructor.prototype.constructor)
```    
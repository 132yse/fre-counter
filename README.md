# fre-counter
A demo for Fre

```javascript
import Fre from 'fre'

class App extends Fre.Component {
  constructor() {
    super()
    this.state = {
      msg: 'loading……'
    }
  }

  mounted(){
    this.state.msg = 'mounted!'
  }

  render() {
    return (
      <div>
        <div id="msg">{this.state.msg}</div>
      </div>

    )
  }
}

Fre.render(<App/>, document.body)

```

API 如上

目前搞定了这么多：
1.对象劫持
2.jsx、react-like 的组件化方案
3.生命周期



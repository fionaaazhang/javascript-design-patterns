# javascript-design-patterns
### difference between watcher pattern and pub-sub pattern
- 在观察者模式中, 观察者是知道subject的存在的, subject 也一直保持着对观察者的记录; 但是发布者和订阅者是互相不知情的, 他们消息盒子代理
- 在发布订阅模式中,组件是松散耦合的, 与观察者模式相反
- 观察者模式大多数时候是同步的,一旦事件触发, subject就会去调用观察者的方法, 而发布订阅模式大多数时候是异步的(通过消息队列)
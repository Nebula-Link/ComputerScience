　
| Pattern              | Refactoring to                                                                                      | Refactoring towards                            | Refactoring away from              |
| :------------------- | --------------------------------------------------------------------------------------------------- | ---------------------------------------------- | ---------------------------------- |
| Adapter              | Extract Adapter; Unify Interfaces with Adapter                                                      | Unify Interfaces with Adapter                  |                                    |
| Builder              | Encapsulate Composite with Builder                                                                  |                                                |                                    |
| Collecting Parameter | Move Accumulation to Collecting Parameter                                                           |                                                |                                    |
| Command              | Replace Conditional Dispatcher with Command                                                         | Replace Conditional Dispatcher with Command    |                                    |
| Composed Method      | Compose Method                                                                                      |                                                |                                    |
| Composite            | Replace One/Many Distinctions with Composite，Extract Composite，Replace Implicit Tree with Composite |                                                | Encapsulate Composite with Builder |
| Creation Method      | Replace Constructor with Creation Methods                                                           |                                                |                                    |
| Decorator            | Move Embellishment to Decorator                                                                     | Move Embellishment to Decorator                |                                    |
| Factory              | Move Creation Knowledge to Factory，Encapsulate Classes with Factory                                 |                                                |                                    |
| Factory Method       | Introduce Polymorphic Creation with Factory Method                                                  |                                                |                                    |
| Interpreter          | Replace Implicit Language with Interpreter                                                          |                                                |                                    |
| Iterator             |                                                                                                     |                                                | Move Accumulation to Visitor       |
| Null Object          | Introduce Null Object                                                                               |                                                |                                    |
| Observer             | Replace Hard-Coded Notifications with Observer                                                      | Replace Hard-Coded Notifications with Observer |                                    |
| Singleton            | Limit Instantiation with Singleton                                                                  |                                                | Inline Singleton                   |
| State                | Replace State-Altering Conditionals with State                                                      | Replace State-Altering Conditionals with State |                                    |
| Strategy             | Replace Conditional Logic with Strategy                                                             | Replace Conditional Logic with Strategy        |                                    |
| Template Method      | Form Template Method                                                                                |                                                |                                    |
| Visitor              | Move Accumulation to Visitor                                                                        | Move Accumulation to Visitor                   |                                    |

> 重构实现: 完全按照该模式的重构步骤进行实现，即该部分整体完全符合对应的模式
> 重构趋向: 重构时可以有选择性的进行步骤重构，使得其趋向于该模式，方便最终实现模式
> 重构去除: 将对应部分的重构模式去除

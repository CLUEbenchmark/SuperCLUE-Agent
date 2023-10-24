# SuperCLUE-Agent
SuperCLUE-Agent: 基于中文原生任务的Agent智能体测评基准

计划更新日期2023-10-20（星期五），敬请期待！

当前请先访问<a href='https://www.cluebenchmarks.com/superclue_agent.html'>官网页面</a>，或<a href='https://www.superclueai.com'>榜单</a>

## 示例

### 工具使用

#### 调用API
调用API，主要考察AI Agent是否可以根据给定API的描述精确调用API，并正确响应API返回的能力。
<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/invoke_api2.png"  width="100%" height="100%"></img>


#### 检索API 
调用API，主要考察AI Agent选择可能解决用户需求的API，并通过阅读文档来学习如何使用它们。
<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/retrieve_api.png"  width="100%" height="100%"></img>

#### 规划API
规划API，估AI Agent在检索和调用API之外的规划能力。考虑到不明确的用户请求（例如预订航班/酒店进行旅行）或者更复杂的请求，
模型可能需要进行多次API调用来解决问题。
<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/plan_api.png"  width="100%" height="100%"></img>

#### 通用工具使用
评估大模型使用通用工具的能力。包括但不限于：使用搜索引擎、浏览网页、操作本地文件、搜索本地文件、使用数据库等等。
<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/general_tool.png"  width="100%" height="100%"></img>


### 任务规划

#### 任务分解
任务分解，它评估的是AI Agent将大型任务分解为较小的、可管理的子目标，从而能够高效地处理复杂任务的能力。
<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/task_decomposition.png"  width="100%" height="100%"></img>

#### 自我反思
该类任务的目标评估AI Agent对过去的行为进行自我批评和反思。从错误中吸取教训，并为未来的步骤进行改进，从而提高最终结果的质量的能力。
<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/reflection.png"  width="100%" height="100%"></img>

#### 思维链（CoT）
该任务主要考察的是AI Agent利用更多的推理时间和过程，将困难的任务分解为更小、更简单的步骤的能力，着重考察AI Agent是如何一步一步通过思考
来解决问题的能力。
<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/cot.png"  width="100%" height="100%"></img>


### 长短期记忆

#### 示例学习（In-context Learning）
示例学习（也称情境学习），是一种特定的提示工程方法，其中任务的示例作为提示的一部分提供给模型。它是一种高阶的涌现能力，
你可以使用现成的大型语言模型（LLM）来解决新任务，而无需进行微调。
<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/incontext_learning.png"  width="100%" height="100%"></img>

#### 长程对话
在现实世界中的长对话中，用户通常会使用大模型谈论几个话题并在其中切换。比如主题检索任务，是通过要求大模型检索由多个主题组成的长对话中的开头和中间过程的主题来测试这种场景。
<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/long_turn_dial3.png"  width="100%" height="100%"></img>


#### 多文档问答
主要考察AI Agent在多个文档中提取并组合答案的能力。
<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/multi_docqa2.png"  width="100%" height="100%"></img>


## 联系方式

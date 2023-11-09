# SuperCLUE-Agent
SuperCLUE-Agent: Agent智能体中文原生任务能力测评基准

[更新日期]2023-10-24, 添加示例

更多信息请访问<a href='https://www.cluebenchmarks.com/superclue_agent.html'>官网页面</a>，或<a href='https://www.superclueai.com'>榜单</a>


<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/SuperCLUE_Agent.png"  width="100%" height="100%"></img>


<img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/superclue_agent_performance1108.png"  width="100%" height="100%"></img>


## 排行榜

### SuperCLUE-Agent三大能力
| 序号 | 模型 | 机构 | 工具使用 | 任务规划 | 长短期记忆 |
|:-:|:-:|:-:|:-:|:-:|:-:|  
| 1 | GPT4 | OpenAI | 90.23 | 81.88 | 66.67 |
|2 |ChatGLM3-Turbo|	清华&智谱AI 	| **73.87** | 	**68.37**	| **77.03**|
| 3 | Claude2-100K | Anthropic | 65.08 | 52.04 | 73.97 |
| 4 | gpt-3.5-turbo | OpenAI | 60.05 | 61.07 | 55.74 |
| 5 | Baichuan2-13B-Chat | 百川智能 | 61.11 | 40.48 | 52.74 |
| 6 | ERNIE-3.5-Turbo | 百度 | 48.23 | 42.62 | 55.41 |
| 7 | MiniMax_Abab5.5 | MiniMax | 51.52 | 46.11 | 42.23 |
| 8 | OpenBuddy-70B | OpenBuddy | 55.31 | 37.58 | 43.13 |  
| 9 | 豆包 | 字节跳动 | 42.54 | 37.92 | 52.72 |
| 10 | ChatGLM2-Pro | 清华&智谱AI | 54.82 | 37.92 | 34.12 |
| 11 | 讯飞星火v2.0 | 科大讯飞 | 48.12 | 39.19 | 36.58 |  
| 12| 通义千问v1.0.8 | 阿里云 | 47.14 | 30.61 | 31.12 |
| 13 | Qwen-7B-Chat | 阿里云 | 39.25 | 28.52 | 37.67 |
| 14 | Llama-2-13B-Chat | Meta | 30.71 | 38.59 | 34.35 |
| 15 | Chinese_Alpaca2_13B | yiming cui | 22.08 | 23.65 | 42.62 |
| 16| ChatGLM2-6B | 清华&智谱AI | 11.87 | 19.09 | 32.33 |
| 17 | 360GPT_S2_V9 | 360 | 13.45 | 20.11 | 28.72 |


### SuperCLUE-Agent十大基础任务
| 模型 | 总分 | 任务分解 | 自我反思 | 思维链 | 调用API | 检索API | 规划API | 通用工具使用 | 多文档QA | 长程对话 | 示例学习 |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|  
| GPT4 | 80.56 | 76.15 | 94.69 | 76.35 | 87.70 | 90.66 | 82.22 | 100.00 | 67.97 | 60.20 | 73.79 |
|ChatGLM3-Turbo	|73.09 |	100.00 |	52.13	|51.00	|49.00	|93.88	|72.00|	81.00	|90.62|	63.00|	78.00|
| Claude2-100K | 63.82 | 42.77 | 64.04 | 51.73 | 52.36 | 74.52 | 73.14 | 61.42 | 59.55 | 68.60 | 94.53 |
| gpt-3.5-turbo | 59.07 | 58.03 | 68.52 | 58.02 | 55.45 | 55.08 | 71.90 | 60.48 | 60.75 | 50.99 | 57.63 |
| Baichuan2-13B-Chat | 52.44 | 65.34 | 29.77 | 28.38 | 32.47 | 81.74 | 61.39 | 69.89 | 58.69 | 43.44 | 57.19 |  
| ERNIE-3.5-Turbo | 48.69 | 69.76 | 39.63 | 20.60 | 42.03 | 46.32 | 58.67 | 47.47 | 64.20 | 67.49 | 36.38 |
| MiniMax_Abab5.5 | 47.07 | 58.40 | 40.90 | 40.49 | 48.75 | 42.39 | 61.97 | 55.52 | 39.27 | 43.78 | 45.29 |
| OpenBuddy-70B | 46.34 | 22.12 | 35.78 | 55.53 | 43.18 | 69.03 | 54.75 | 56.65 | 35.10 | 47.31 | 47.42 |
| 豆包 | 43.95 | 32.12 | 41.61 | 41.25 | 38.40 | 45.74 | 54.06 | 31.45 | 48.07 | 52.99 | 58.26 |
| ChatGLM2-Pro | 43.52 | 27.31 | 45.13 | 42.91 | 33.44 | 82.11 | 64.66 | 39.46 | 17.16 | 39.81 | 46.33 |
| 讯飞星火v2.0 | 41.95 | 39.24 | 44.23 | 35.67 | 44.97 | 53.16 | 41.19 | 54.78 | 35.07 | 36.96 | 39.59 |
| 通义千问v1.0.8 | 37.32 | 14.93 | 32.59 | 45.22 | 37.37 | 63.60 | 40.96 | 48.07 | 23.54 | 45.21 | 25.31 |
| Qwen-7B-Chat | 35.57 | 26.00 | 32.76 | 28.70 | 48.43 | 53.19 | 19.90 | 37.04 | 36.44 | 43.44 | 34.46 |
| Llama-2-13B-Chat | 34.18 | 50.52 | 35.97 | 30.59 | 20.89 | 45.03 | 30.01 | 28.99 | 24.29 | 38.57 | 41.46 |
| Chinese_Alpaca2_13B | 28.74 | 33.63 | 26.36 | 13.37 | 22.23 | 25.79 | 18.70 | 23.64 | 42.22 | 45.00 | 42.05 |
| ChatGLM2-6B | 20.18 | 10.81 | 31.93 | 16.83 | 19.84 | 10.82 | 3.85 | 15.98 | 37.65 | 35.43 | 25.10 |
| 360GPT_S2_V9 | 20.07 | 12.21 | 30.01 | 18.98 | 7.62 | 17.42 | 8.45 | 23.00 | 19.30 | 41.58 | 27.19 |


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


## 讨论、测评与交流

<br/>SuperCLUE-Agent榜单会定期进行更新，会纳入更多可用中文大模型。欢迎对大模型评测感兴趣的个人和机构联系与交流。<br/><br/>

<br/><h2 id="discuss">讨论交流与使用</h2>
<p float="left"><br>  <img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/agent_group.jpeg"  width="30%" height="30%"></img>
  <img src="https://github.com/CLUEbenchmark/SuperCLUE-Agent/blob/main/resources/img/brightmart_s.jpeg"  width="30%" height="30%"></img>
</p> 


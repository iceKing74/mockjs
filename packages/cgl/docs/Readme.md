# mockjs

## Core

### Basic
> MockJs的基础功能，生成基础的随机数，是复杂类型和规则的基石，复杂类型和规则大多都是基于基础随机函数生成
  - [Basic](core/basic.md)
### Rule
> 规则（Rule）是MockJs的核心概念，通过Rule来定义一类特定的复杂随机数据，可以定义各类，Rule支持动态增减
  - [RuleGenerator](core/rule/RuleGenerator.md)
  - [RuleManager](core/rule/RuleManager.md)

## Rules
> 规则实例，规则实例是规则的实例，本目录会内置基于基础随机函数的基础规则实例
- [getRuleInstance](rules/index.md)
- [MockString](rules/MockStringRule.md)
- [PersonSleep](rules/PersonSleepRule.md)

## Extends
> 复杂数据类型，基于基础随机函数和其他复杂随机函数，往往是某种业务实体
- [Person](extends/person.md)
- [Random（就是core中的Basic）](basic.md)

## Schema
> 模板处理，基于规则的模板处理方法，往往用于mock复杂对象或列表
+ [Schema](schema.md)

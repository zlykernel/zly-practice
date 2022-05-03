## tdd-practice 
tdd(测试驱动设计) 不对代码做测试就像“上完厕所不洗手” - Tim Bray

1. 方法论
2. 测试阶段
+ Setup 初始化
+ Exercise 执行测试
+ Verify 验证结果
+ Teardown 复原
    + State Verification 状态验证
        + Delta Verification 增量状态验证
    + Behavior Verification 行为验证
## TDD的单元测试
+ Kent Beck：通过构造恰当粒度的黑盒功能测试驱动开发
+ Martin Folwer：DD 社区所谓的单元测试到底是“能提供快速反馈的低成本的研发测试”
+ Martin Fowler：建议将 TDD 中的测试叫作极限单元测试（Xunit Testing），以区别于行业中的叫法

# 工具
+ junit5
+ mockito
+ idea refactor功能
# EVM代码整体结构

```shell
~/go-ethereum/core/vm

➜ tree . -L 1      
.
├── README.md
├── analysis.go                     // 分析合约字节吗，标记是否是跳转目标(jumpdest)
├── analysis_test.go
├── common.go                       // 一些公共的方法
├── contract.go                     // 智能合约数据结构
├── contracts.go                    // 预编译合约集
├── contracts_fuzz_test.go
├── contracts_test.go
├── doc.go                          // 
├── eips.go                         // 一些EIP的实现
├── errors.go
├── evm.go
├── gas.go
├── gas_table.go
├── gas_table_test.go
├── instructions.go
├── instructions_test.go
├── interface.go
├── interpreter.go
├── interpreter_test.go
├── jump_table.go
├── jump_table_export.go
├── jump_table_test.go
├── logger.go
├── memory.go
├── memory_table.go
├── memory_test.go
├── opcodes.go
├── operations_acl.go
├── runtime
├── stack.go
├── stack_table.go
└── testdata

3 directories, 31 files

```
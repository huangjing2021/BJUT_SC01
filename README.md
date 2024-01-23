#EN

This dataset uses SCStudio, a security analysis tool developed by Tsinghua University, for labeling. This tool conducts analysis on the Solidity language and integrates open source tools such as Oyente and Pied-Piper to build a comprehensive testing system, supporting the detection of most types of smart contract vulnerabilities and providing a high level of reliability.

This dataset contains 148,384 contracts, with 8 attributes including 'address (address)', 'contractCode (bytecode)', 'timestamp (timestamp)', 'createValue (creation value)', 'createdBlockNumber (creation block number)', 'createdTransactionHash (creation transaction hash)', 'creationCode (creation code)', and 'creator (creator)'. It has 29 vulnerability labels, including 'Integer overflow or underflow', 'Unchecked call return value', 'Unprotected ether withdrawal', 'Unprotected self-destruct instruction', 'Reentrancy', 'Assert violation', 'Delegatecall to untrusted callee', 'DoS with failed call', 'Timestamp dependence', 'Weak sources of randomness from chain attributes', 'Write to arbitrary storage location', 'Arbitrary jump with function type variable', 'Call stack depth limit exceeding', 'Contract contains unknown address', 'Use of call function with no data', 'Multiplication after division', 'Using approve function of the ERC-20 token standard', 'Return value is always false', 'ERC-20 transfer should throw', 'Extra gas consumption', 'Locked money', 'Overpowered role', 'Redundant fallback function', 'Unsafe send', 'Worse readability with revert', 'ArbitraryTransfer problem', 'GenerateToken problem', 'DestroyToken problem', 'FrozeAccount problem', 'DisableTransfer problem'. Additionally, the label 'flag' indicates whether the contract has a vulnerability, with "0" representing no vulnerability and "1" representing a vulnerability. To obtain the source code, please visit the XBlock official website for download, at the address:http://xblock.pro/#/dataset/17


#CN

本数据集使用清华大学开发的安全分析工具SCStudio进行检测，该工具针对Solidity语言进行分析，集成了Oyente,Pied-Piper等多种开源工具构建一个综合的测试系统，支持对大多数类型的智能合约漏洞检测，具有较高的可信度。

本数据集共148384份合约，其包含'address(地址)', 'contractCode(字节码)', 'timestamp(时间戳)', 'createValue(创建值)','createdBlockNumber(创建区块号)', 'createdTransactionHash(创建交易哈希值)', 'creationCode(创建码)','creator(创建者)'等8种属性，具有'Integer overflow or underflow',
  'Unchecked call return value', 'Unprotected ether withdrawal',
  'Unprotected self-destruct instruction', 'Reentrancy',
  'Assert violation', 'Delegatecall to untrusted callee',
  'DoS with failed call', 'Timestamp dependence',
  'Weak sources of randomness from chain attributes',
  'Write to arbitrary storage location',
  'Arbitrary jump with function type variable',
  'Call stack depth limit exceeding', 'Contract contains unknown address',
  'Use of call function with no data', 'Multiplication after division',
  'Using approve function of the ERC-20 token standard',
  'Return value is always false', 'ERC-20 transfer should throw',
  'Extra gas consumption', 'Locked money', 'Overpowered role',
  'Redundant fallback function', 'Unsafe send',
  'Worse readability with revert', '`ArbitraryTransfer` problem',
  'GenerateToken problem', 'DestroyToken problem', 'FrozeAccount problem',
  'DisableTransfer problem'等29种漏洞标签。
另外标签'flag'表示该合约是否存在漏洞，其中，“0”代表不存在漏洞，“1”代表存在漏洞。
若要获取源码，请前往XBlock官方网站下载，地址是 http://xblock.pro/#/dataset/17

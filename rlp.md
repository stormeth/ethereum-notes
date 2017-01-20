
See spec here.

https://github.com/ethereum/wiki/wiki/RLP

"".to_rlp
=> [128]

[""].to_rlp
=> [193, 128]

"a".to_rlp
=> [97]

["a"].to_rlp
=> [193, 97]

"0".to_rlp
 => [48]

["0"].to_rlp
  => [193, 48]

"01".to_rlp
 => [130, 48, 49]

["01","02"].to_rlp
 => [198, 130, 48, 49, 130, 48, 50]

"ab".to_rlp
 => [130, 97, 98]

["ab"].to_rlp
 => [195, 130, 97, 98]

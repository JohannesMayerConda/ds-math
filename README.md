<h2>DSMath
  <small class="text-muted">
    <a href="https://github.com/dapphub/ds-math"><span class="fa fa-github"></span></a>
  </small>
</h2>

This library is a fork of <a href="https://github.com/dapphub/ds-math">dapphub's ds-math</a> that changed the code to a library and shows a sample implementation. Via ds-math you can e.g. multiply decimal numbers where both numbers are bellow zero which isn't as easy using OpenZeppelin <a href="https://github.com/OpenZeppelin/openzeppelin-solidity/blob/master/contracts/math/SafeMath.sol">SafeMath</a>.

```solidity
1.1 * 2.2 == 2.42

//Regular integer arithmetic adds orders of magnitude:

110 * 220 == 24200

// Wad arithmetic does not add orders of magnitude:

wmul(1.1 ether, 2.2 ether) == 2.42 ether
```

More details see original repository: <a href="https://github.com/dapphub/ds-math">dapphub's ds-math</a>

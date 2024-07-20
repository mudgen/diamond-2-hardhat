# Commending Jake Mc (https://github.com/startswithaj)

Earlier this year Jake found a rare bug in the diamond-2 and diamond-2-hardhat implementations. This is despite smart contract security audits in the past that did not find this bug.

Specifically the bug was that selector tracking was broken when adding and removing the payable selector 0x00000000 as a function in a diamond.

He wrote a clear description of the bug and created a proof of concept to show and prove the bug. He created a pull request that fixes the bug and adds a test that hereafter tests for the existence of the bug. His description of the bug and pull request is here: https://github.com/mudgen/diamond-2-hardhat/pull/11
His pull request was merged so the bug no longer exists.

I commend Jake for the way that he reported, fixed and tested this bug. Developers like him make better open source software.
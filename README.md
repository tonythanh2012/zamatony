# zamatony
tony tao 5 commit cho zama
Deploy xong nhớ MINT sẽ có token ERC 721


// SPDX-License-Identifier: MIT
// Compatible with OpenZeppelin Contracts ^5.0.0
pragma solidity ^0.8.0;
import "@openzeppelin/contracts/token/ERC721/ERC721.sol";

contract lehieukemNFT is ERC721 {
    uint256 public tokenId;

    constructor() ERC721("lehieukemCollection", "LKEM") {
        tokenId = 0;
    }

    function mint() public {
        _mint(msg.sender, tokenId);
        tokenId++;
    }
}
echo "Commit 2 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-10T06:10:02" GIT_COMMITTER_DATE="2025-06-10T06:10:02" git commit -m "Commit 2"

echo "Commit 1 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-10T06:01:01" GIT_COMMITTER_DATE="2025-06-10T06:01:01" git commit -m "Commit 1"

Commit 1 line
Commit 2 line
Commit 3 line
Commit 4 line
Commit 5 line
Commit 6 line
Commit 7 line
Commit 8 line
Commit 9 line

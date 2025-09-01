
# Simple Storage Smart Contract

## 📌 Description
A basic Solidity contract that stores an integer and allows incrementing and decrementing its value.

## ✨ Features
- Stores an integer value.
- `increment()` increases the value by 1.
- `decrement()` decreases the value by 1.
- Value can be read publicly.

## 🚀 How to Run
1. Open [Remix IDE](https://remix.ethereum.org).
2. Create a new file `SimpleStorage.sol` inside a `contracts/` folder.
3. Paste the contract code.
4. Compile using Solidity `0.8.x`.
5. Deploy using **Remix VM (London)**.
6. Interact with:
   - `increment()` → increases stored value.
   - `decrement()` → decreases stored value.
   - `value` → read current value.

## 🧪 Example
- Initial value = `0`
- Call `increment()` → value = `1`
- Call `increment()` again → value = `2`
- Call `decrement()` → value = `1`

## 📜 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

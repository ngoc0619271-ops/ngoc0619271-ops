### Tiket — Tickets that cannot be faked or spent twice

A screenshot of a ticket is not a ticket.

Buying escrows the price into the contract and records the ticket on-chain. At the door, check-in settles the escrow to the organizer and flips the ticket to Used in the same transaction — spent exactly once.

|  |  |
|---|---|
| Live | [tiket-mu.vercel.app](https://tiket-mu.vercel.app) |
| Code | [ngoc0619271-ops/Tiket](https://github.com/ngoc0619271-ops/Tiket) |
| Stack | Soroban (Rust) · Next.js · TypeScript |
| Contract | [`CDIQ6JCW6U…`](https://stellar.expert/explorer/public/contract/CDIQ6JCW6UGLKBNINAJKTDRICA5ZRP5MNS6HGB7I3NRTYRTDRDHO7Y6I) |

Refund before the event returns the escrow. That is what makes the escrow fair rather than just a lock: the buyer's money is not stranded if plans change.

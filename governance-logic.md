_Note: this is a work in progress. It follows the philosophy of "working with the garage door open". This document needs your feedback. Feel free to reach out via twitter (@abratusz), telegram (@abratusz), or email (ala.tusz.am@skiff.com)._

# Preamble: 
"[The Cosmos Hub] is a network of [ATOM holders] who share common purpose, and are the only ones who hold the power to execute actions that manage [the Hub's] shared resources." ([Anticapture](https://spengrah.mirror.xyz/f6bZ6cPxJpP-4K_NB7JcjbU0XblJcaf7kVLD75dOYRQ))

# The Interchain: 
- The Interchain is a network of state-machines connected by the Inter-Blockchain Communication protocol (IBC).
- IBC is a shared Interchain resource that was funded by the Cosmos Hub. 

# The Cosmos Hub: 
- The Cosmos Hub is a key economic, meta-political, and coordination zone in the Interchain that is composed of ATOM holders. ([Cosmos Hub Charter](https://forum.cosmos.network/t/discussion-working-draft-of-cosmos-hub-charter/7803) and [Community Charter Review](https://docs.google.com/document/d/1ay8AdBq6fZ8muQ093p-YfwvtPLH5TV8bJXOfi-LKwbI/edit#))
- Anyone that owns any piece of an ATOM token is an ATOM holder. 
- ATOM holders may become citizens by staking ATOM. (needs further definition, or in the philosophy of Hypha's draft, exclusion so as not to become prescriptive). 
- Citizens dictate the allocation of the Cosmos Hub shared resources via governance. (Daniel Ospina mentioned that we may want to include a more comprehensive approach here). 

# Governance: 
- Governance recursively includes every action related to influencing the shared resources of the Cosmos Hub.
- One of the essential responsibilities of Cosmos Hub governance is to resist capture of the Cosmos Hub by malicious actors, or those who seek to use the shared resources for ends that do not align with the vision of its citizens. 
- Capture-resistance is a practice, and each Cosmos citizen has a duty to uphold capture-resistance in thought and action. Any thought or action that seeks to increase capture-resistance or further the collective mission of the Cosmos Hub (which is?) can be considered an act performed in good-faith. 
- Slashing should not ever be used to retroactively alter the token amount in wallets. Slashing of tokens is reserved exclusively for in-protocol, deterministic removal of token holdings for actions that damage the network (for example equivocation faults or double signing, undue downtime, or vetoed governance proposals). 
- Voting power shall be linked to both token quantity and reputation. Voting power reputation multipliers may only grow via not acting in bad-faith. 
- On-chain governance can and should be used to both bestow or diminish authorities of Cosmos citizens. 
- On-chain governance shall never bestow authorities that reduce capture or censorship-resistance of the Cosmos Hub. 

# Freedom to Disobery
_Language source: [Cosmos Hub Charter](https://forum.cosmos.network/t/discussion-working-draft-of-cosmos-hub-charter/7803)_
- The freedom to disobey is a core tenet of capture-resistance. All Cosmos citizens have a right to publish freely via any means available.
- Any publication produced in good-faith pertaining to Cosmos governance by any Cosmos citizen on any platform is a valid reason for initiating change. (this is probably an unnecessary clause)

## On-chain Governance:
- Cosmos Hub citizens use on-chain proposals to reach consensus about governance decisions.
- The on-chain governance process is determined via the binary run by the Cosmos Hub validators that collectively have greater than 2/3rds of total staked tokens delegated to them. 
- Cosmos citizens can alter on-chain governance processes via a software-upgrade proposal or a gov-param proposal. 
- Cosmos citizens may choose to adopt new on-chain governance processes at any time, but must explicitly define how any new process affect Cosmos citizens' power over shared-resources and their ability to influence such resources. 

### On-chain reptutation
- Governance slashing, or the act of reducing the voting power of any citizen is considered a valid sanction for actors acting in bad-faith. This does not alter the token balance of the wallet or validator being sanctioned, but it does alter the power and influence they have in governance. ([note](https://twitter.com/abratusz/status/1630146232696942594))
- The Cosmos Hub network may governance slash an actor via a censure proposal. 
- It is the burden of the proposer to provide sufficient evidence for censuring another citizen. All citizens are considered to be acting in good-faith unless proven otherwise. 
- Any proposal that does not contain sufficient evidence or appears as an ad-hominem attack may be vetoed, as that proposal directly infringes upon a minority interest.
- Cosmos citizens carry no permanent reputation. Voting power recovers over time, though consecutive slashing proposals within a short time frame will lead to a slower rate of power-regrowth. 
- Governance boosting, or the act of increasing the voting weight of any citizen, is prohibited. Reducing voting power via governance slashing results in increasing voting power of all other wallets, proportionately. This is to enable good actors to emerge naturally and acknowledges non-action as a valid method of acting in good-faith. 
- If a validator is governance slashed, all wallets delegating to that validator are also governance slashed. (what attack vectors does this open up? what is another way to do on-chain reputation systems?) The validator suffers a longer voting power recovery rate than its delegators.

## Off-chain Governance: 
- A proposal is not complete after it passes on-chain governance. The execution and feedback stage are deeply relevant to the governance process.
- Off-chain governance is the foundation of on-chain governance.
- Off-chain governance encompasses every aspect of decision making that does not happen on-chain. (does this make sense?)
- Off-chain governance processes may arise at any time with or without social consensus. 
- Social consensus is important to formally recognize and ratify off-chain governance processes and their implications. 
- Social consensus is reached via an on-chain proposal called a signaling proposal. 
- Reaching social consensus implies that any deviation from that consensus via on-chain action requires published justification. Failing to publish justification may amount to a censure proposal. (is this effective? how to deal with issues of jurisprudence for on-chain governance? should social consensus be "enforced" by any means other than a fork?)
- Implications of off-chain governance may be enforceable either off-chain via social action or on-chain via governance, or culturally via a fork.  
- When possible, ratified processes should seek expression via on-chain governance. If this does not occur, governance processes are expected to be upheld via social-actions. (contradictory?)

# Shared Resource Governance
## Raising on-chain proposals
- All proposals must undergo a feedback period.
- All good-faith feedback is considered valid and should be responded to by the proposers. 
- Conflicts of interest should be stated at the outset. 
- Proposers must disclose relevant context. Relevant context includes any information that is relevant to decision-makers voting on the proposal. An example of relevant context for community pool spend proposals is: funding received or applied for. 
- Failure to abide by any of the following is considered valid rationale to reject a proposal. 

## Voting on on-chain proposals
- Disclosure of vote-rationale is considered a core-aspect of the Cosmos Proof of Stake model. Validators must disclose their vote rationale via on-chain memos that contain links to persistent and addressable content. 
- Failure to disclose vote rationale is a justification to censure a validator. 

python_lib(solidity_contracts_components_sol
    PREFIX starkware/solidity/components
    FILES
    FactRegistry.sol
    GovernedFinalizable.sol

    LIBS
    solidity_contracts_interfaces_sol
)

python_lib(governance_contract_sol
    PREFIX starkware/solidity/components
    FILES
    GenericGovernance.sol
    Governance.sol
    GovernanceStorage.sol
    Operator.sol

    LIBS
    governance_interface_sol
)

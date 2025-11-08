# add-function-reset-draft
function resetMyGarage() external override {
        delete garages[msg.sender];
    }

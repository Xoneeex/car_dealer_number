    local success = exports['car_dealer_number']:StartCarDealerNumber()
    if success then
        ESX.ShowNotification('Udane')
    elseif not success then
        ESX.ShowNotification('Nie Udane')
    end
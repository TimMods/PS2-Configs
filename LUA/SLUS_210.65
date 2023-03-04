apiRequest(1.0)
local eeObj = getEEObject()
local emuObj = getEmuObject()
local patcher = function()
eeObj.WriteMem32(0x001D77C8,0x100000B4)
end
emuObj.AddVsyncHook(patcher)

--Speed Fix
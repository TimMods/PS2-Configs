apiRequest(1.0)
local eeObj = getEEObject()
local emuObj = getEmuObject()
local patcher = function()
eeObj.WriteMem32(0x001D79D8,0x100000B4)
end
emuObj.AddVsyncHook(patcher)

-- Fix the horizontal lines after the background
emuObj.SetGsTitleFix( "forceSimpleFetch", "reserved", { texMode=1 } )
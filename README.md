--GETTING THE NOTIFICATIONS
local notifs = loadstring(game:HttpGet('https://raw.githubusercontent.com/sourcersknz/Notification/refs/heads/main/FE2Notifs.lua'))()

--NOTIFYING
notifs.alert(TEXT, COLOR3 (optional), TIME (4.5 if nil), special ('rainbow' for rainbow))

--Example
notifs.alert('Hello!') -- simple white "Hello!" notification lasting 4.5s
notifs.alert('Hello!',Color3.new(0,1,0)) -- simple green "Hello!" notification lasting 4.5s
notifs.alert('Hello!',Color3.new(0,1,0),2) -- simple green 'Hello!' notification lasting 2s
notifs.alert('Hello!',nil,2,'rainbow') -- rainbow 'Hello!' notification lasting 2s

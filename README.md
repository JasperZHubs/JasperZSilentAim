getgenv().phyx_target = {
    ["Main"] = {
       ["Prediction"] = 0.16253,
       ["Partz"] = "UpperTorso",
       ["Air Delay"] = 0.2, -- // this is NOT an prediction, don't mess with it if you don't know how to set it properly. if it's too high, try 0.18 and then any numbers after that. like 0.181. ( based on latency, just adjust it )
       ["AutoPred"] = false,
       ["Dot"] = true,
       ["No Floor Shots"] = true,
       ["Offsets"] = { true, value = 1.1605 } -- // recommended; 0.16108 for 110+ ping. NOT an prediction. Create your own offset! ts is new and different from other locks!!
    },
    ["Aim Assist"] = {
       ["Cam Enabled"] = false,
       ["Partz"] = "UpperTorso",
       ["Use Smoothness"] = true,
       ["Smoothness Value"] = 0.165
    },
    ["GUIs"] = {
       ["Save Position"] = false,
       ["Auto Air"] = true,
       ["Buy Items"] = true, -- // Only works on VFS games.
       ["Reset"] = true,
       ["Leave"] = false,
       ["Bullet Tp"] = true, -- //  works most dh games
       ["Trigger Bot"] = { false, delay = 5.5 }, -- // under maintenance, but works without delay.
       ["Macro"] = { true, type = "Legit" } -- // Can be: "Legit" , "Speed" , "CFrame".
    }
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/plah911/phyx/refs/heads/main/new%20betaaa"))();

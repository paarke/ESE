_G.Ui_Hide = false
_G.KaitunConfig = {
    ["Start Farm"] = true,
    -- all melee is already do with it self
    -- auto activate list ( Auto Do List )
    --[[ //auto activate list//
        GodHuman, all melee
        get god human material
        random fruit , store fruit
        smart code redeem

        / sea 1
        auto go sea 2
        skip farm level
        saber
        kill Greybeard (bisento v2)

        / sea 2
        auto go sea 3
        kill darkbeard
        race v2
        bartilo

        / sea 3
        kill boss

        dough awaking
        CDK
        elite hunter
    ]]
    ["Auto Fruit"] = true, -- tween to fruit

    ["RedeemCode Level"] = 2,

    ["White Sreen"] = true,

    ["LimitFragment"] = 100000,

    -- item

    ["Boss List"] = { -- put boss for farm item ---pls dont put boss that have requirement (like Saber boss dofrmigo) because it already kill if can
        "The Saw [Lv. 100] [Boss]",
        "Greybeard [Lv. 750] [Raid Boss]",
    
        "Darkbeard [Lv. 1000] [Raid Boss]",
        "Cursed Captain [Lv. 1325] [Raid Boss]",

        "Captain Elephant [Lv. 1875] [Boss]",
        "Soul Reaper [Lv. 2100] [Raid Boss]",
        "Dough King [Lv. 2300] [Raid Boss]",
        "Cake Prince [Lv. 2300] [Raid Boss]",
        "rip_indra True Form [Lv. 5000] [Raid Boss]",
        "Beautiful Pirate [Lv. 1950] [Boss]",
        "Cake Queen [Lv. 2175] [Boss]"
    },

    -- sea 1
    ["PlayerHunter"] = true, -- will do skip lvl too
    ["Player Hunter Hop"] = false,

    -- sea 2
    ["Auto Factory"] = true,
    ["Rengoku"] = true,
    ["Sea 3 Hop"] = false, -- hop to find fruit
    ["Race v3"] = true,
    
    -- sea 3
    ["CDK"] = true,
    ["Tushita"] = true,
    ["Yama"] = true,
    ["Soul Guitar"] = true,

    -- Add On
    ["Farm When Lvl Max"] = "Katakuri", -- Bone , Katakuri , Coco
    ["Race Lock"] = "notlock", -- Human , Mink , Fishman , put other mean not lock
    ["FPS Cap"] = 35,

    ["Buy Haki Color"] = true, -- will buy only Snow White,Pure Red,Winter Sky
    ["Auto Legendary Sword"] = true,
    ["Auto TTK"] = true,

    -- Sword
    ["Mastery Sword"] = true, -- will farm mastery
    ["Select Rarity"] = {"Mythical","Legendary"}, -- Common , Uncommon,Rare,Legendary,Mythical

    -- Fruit
    ["Select Main Devil Fruit Sniper"] = {"Dragon-Dragon","Spirit-Spirit","Venom-Venom","Dough-Dough"}, -- if have will eat
    ["Select Sub Devil Fruit Sinper"] = {"Ice-Ice","Sand-Sand","Dark-Dark","Quake-Quake","Light-Light","Buddha-Human:Buddha"}, -- will eat if not have main fruit
    ["Allow Eat Fruit In Inventory"] = false,
    ["Start Sniper"] = true,
    
    -- Fruit2
    ["Safe Fruit"] = {"Dragon-Dragon","Spirit-Spirit","Venom-Venom","Dough-Dough","Buddha-Human:Buddha"}, -- will not use this fruit to raids or anyting

    -- Webhook
    ["Link Webhook"] = "",
    ["Start Webhook"] = false,
    ["Webhook Mode"] = "Send Every .. min", -- "Send Every .. min","Send On Level Max","Send On Level Max And Every .. min"
    ["Webhook Minute"] = 5, -- mean 10 Minute
    ["tag user"] = false,
    ["Send Test Webhook"] = false,
}

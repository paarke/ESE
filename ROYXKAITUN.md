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

        / sea 2
        auto go sea 3
        kill darkbeard
        race v2
        bartilo

        / sea 3
        kill soul reaper,
        kill dough king,
        kill cake prince
        kill rip indra
        kill Beautiful Pirate

        dough awaking
        elite hunter

        

    ]]
    ["Auto Fruit"] = true, -- tween to fruit

    ["RedeemCode Level"] = 2,

    ["Black Sreen"] = true,

    ["LimitFragment"] = 56789,

    -- sea 1
    ["PlayerHunter"] = true, -- will do skip lvl too
    ["Player Hunter Hop"] = false,

    -- sea 2
    ["Auto Factory"] = true,
    ["Rengoku"] = false,
    ["Sea 3 Hop"] = true, -- hop to find fruit
    ["Race v3"] = true,
    
    -- sea 3
    ["CDK"] = true,
    ["Tushita"] = true,
    ["Yama"] = true,
    ["Soul Guitar"] = true,

    -- Add On
    ["Farm When Lvl Max"] = "Katakuri", -- Bone , Katakuri , Coco
    ["Race Lock"] = "notlock", -- Human , Mink , Fishman , put other mean not lock
    ["FPS Cap"] = 50,

    ["Buy Haki Color"] = true, -- will buy only Snow White,Pure Red,Winter Sky
    ["Auto Legendary Sword"] = true,
    ["Auto TTK"] = true,

    -- Sword
    ["Mastery Sword"] = true, -- will farm mastery
    ["Select Rarity"] = {"Mythical","Legendary","Rare"}, -- Common , Uncommon,Rare,Legendary,Mythical

    -- Fruit
    ["Select Main Devil Fruit Sniper"] = {"Dragon-Dragon","Spirit-Spirit","Venom-Venom","Dough-Dough","T-Rex-T-Rex","Leopard-Leopard","Kitsune-Kitsune","Mammoth-Mammoth"}, -- if have will eat
    ["Select Sub Devil Fruit Sinper"] = {"Buddha-Human:Buddha","Sound-Sound","Blizzard-Blizzard","Rumble-Rumble","Control-Control","Bird:Phoenix-Bird:Phoenix","Shadow-Shadow","Flame-Flame","Ice-Ice","Love-Love","Light-Light","Magma-Magma","Quake-Quake"}, -- will eat if not have main fruit
    ["Allow Eat Fruit In Inventory"] = false,
    ["Start Sniper"] = true,
    
    -- Fruit2
    ["Safe Fruit"] = {"Dragon-Dragon","Spirit-Spirit","Venom-Venom","Dough-Dough","T-Rex-T-Rex","Leopard-Leopard","Kitsune-Kitsune","Mammoth-Mammoth","Buddha-Human:Buddha","Sound-Sound","Blizzard-Blizzard","Rumble-Rumble","Control-Control","Bird:Phoenix-Bird:Phoenix","Shadow-Shadow"}, -- will not use this fruit to raids or anyting
}
_G.Key = "914R1-PJFQ9-X9PLV"
_G.DiscordId = "1059102801407524965"
loadstring(game:HttpGet("https://raw.githubusercontent.com/Natsuhanaki/Royx_PC/main/loader.lua"))();

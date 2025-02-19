loadstring(game:HttpGet(("https://raw.githubusercontent.com/daucobonhi/Ui-Redz-V2/refs/heads/main/UiREDzV2.lua")))()

       local Window = MakeWindow({
         Hub = {
         Title = "TBoy Roblox",
         Animation = "Youtube: TBoy Roblox"
         },
        Key = {
        KeySystem = false,
        Title = "Key System",
        Description = "",
        KeyLink = "",
        Keys = {"1234"},
        Notifi = {
        Notifications = true,
        CorrectKey = "Running the Script...",
       Incorrectkey = "The key is incorrect",
       CopyKeyLink = "Copied to Clipboard"
      }
    }
  })

       MinimizeButton({
       Image = "http://www.roblox.com/asset/?id=83190276951914",
       Size = {60, 60},
       Color = Color3.fromRGB(10, 10, 10),
       Corner = true,
       Stroke = false,
       StrokeColor = Color3.fromRGB(255, 0, 0)
      })
      
------ Tab
     local Tab1o = MakeTab({Name = "Script Farm"})
     
------- BUTTON
    
    AddButton(Tab1o, {
     Name = "Ko biết(xài saitama)",
    Callback = function()
	  loadstring(game:HttpGet("https://pastebin.com/raw/EMWSLp9A"))()
 AddButton(Tab1o, {
     Name = "JK(xài saitama)",
    Callback = function()
	 loadstring(game:HttpGet("https://raw.githubusercontent.com/UltimateKJPlayer/JK-MOVESET-V1.0/refs/heads/main/JK%20MOVESET%20V1.0%20(1).txt"))()

- 👋 Hi, I’m @Pranaychaudhary143
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Pranaychaudhary143/Pranaychaudhary143 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---> 
#function love.filedropped(file)
    -- Open for reading
    file:open("r")
    
    -- Iterate over the lines
    local i = 0
    for line in file:lines() do
        i = i + 1
        levels[i] = line
        print(i, levels[i]) -- Notice the parentheses missing in your code
    end
    
    -- Close the file
    file:close()
end

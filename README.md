using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using Discord.Commands;

namespace discord_bot.Modules
{
    public class Class1 : ModuleBase<SocketCommandContext>
    {
        [Command("Nigga")]
        public async Task Nigga()
        {
            ReplyAsync("Balls");
        }
    }
    public class Class2 : ModuleBase<SocketCommandContext>
    {
        [Command("TellMeAJoke")]
        public async Task TellMeAJoke()
        {
            ReplyAsync("Syno is a retard");
        }
    }
    public class Class3 : ModuleBase<SocketCommandContext>
    {
        [Command("ni")]
        public async Task FORTNITE()
        {
            ReplyAsync("gger");

        }
    }

}

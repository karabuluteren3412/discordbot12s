import discord
from discord.ext import commands
import random

intents = discord.Intents.default()
bot = commands.Bot(command_prefix='$', intents=intents)

# Güzel dilekler listesi
dilekler = [
    "Bugün her şey gönlünce olsun!",
    "Mutluluk ve huzur seninle olsun!",
    "Hayat sana en güzel sürprizlerini hazırlasın!",
    "Yüzünden gülümseme, kalbinden umut eksik olmasın!",
    "Güzel günler seni bekliyor!",
    "Başarıların daim, yolun açık olsun!",
    "İyi ki varsın, hep gülümse!",
    "Dilediğin tüm güzellikler seni bulsun!",
    "Sağlık, mutluluk ve bol şans seninle olsun!"
]

@bot.command()
async def dilek(ctx):
    rastgele_dilek = random.choice(dilekler)
    await ctx.send(f"{ctx.author.mention} 💫 {rastgele_dilek}")

# Botu başlat
bot.run("senin tokenin")

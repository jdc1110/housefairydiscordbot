# housefairydiscordbot
집요정 봇 코드


import discord

client = discord.Client()


@client.event
async def on_ready():
    print("준비중...")
    print("준비완료! 이제 다른 작업을 하러 가셔도 됩니다! 절대로 창을 닫지 마세요!")
    game = discord.Game("집요정과의 실시간 채팅")
    await client.change_presence(status=discord.Status.online, activity=game)


@client.event
async def on_message(message):
    if message.content.startswith("!디코봇 어케 만듬"):
        await message.channel.send("선구글링")

    if message.content.startswith("!명령어"):
        await message.channel.send("2020.06.29 기준 !디코봇 어케 만듬, !명령어, !도움, !ㅎㅇ, !섹스, !사랑해, !망겜, !갓겜, !생일선물, !집요정병신, !나의 능지는, !학원갔다올게, !마일스톤, !곤란해요여신님, !집요정봇초대, !집요정귀여워, !집요정봇소스코드, !와!")

    if message.content.startswith("!도움"):
        await message.channel.send("!명령어 쳐 병신아")

    if message.content.startswith("!ㅎㅇ"):
        await message.channel.send("ㅎㅇ")

    if message.content.startswith("!섹스"):
        await message.channel.send("니 밴 아무튼 밴")

    if message.content.startswith("!사랑해"):
        await message.channel.send("ㅗ")

    if message.content.startswith("!망겜"):
        await message.channel.send("레인보우 식스 시즈")

    if message.content.startswith("!갓겜"):
        await message.channel.send("카운터 스트라이크 글로벌 오펜시브")

    if message.content.startswith("!생일선물"):
        await message.channel.send("생일이 언제인지 먼저 알려주세요, 알려줘도 생일선물은 안줄껍니다")

    if message.content.startswith("!집요정병신"):
        await message.channel.send("그래")

    if message.content.startswith("!나의 능지는"):
        await message.channel.send("미안한데 능지차이 ㅈㄴ 나")

    if message.content.startswith("!학원갔다올게"):
        await message.channel.send("잘 갔다왕")

    if message.content.startswith("!마일스톤"):
        await message.channel.send("@Seŕhìo Markína#7777")

    if message.content.startswith("!곤란해요여신님"):
        await message.channel.send(":mad:")

    if message.content.startswith("!집요정봇초대"):
        await message.channel.send("https://discord.com/oauth2/authorize?client_id=726761930836148225&scope=bot")

    if message.content.startswith("!집요정귀여워"):
        await message.channel.send("아잉잉 너무 부끄러웠")

    if message.content.startswith("!집요정봇소스코드"):
        await message.channel.send("https://github.com/jdc1110/housefairydiscordbot")

    if message.content.startswith("!와!"):
        await message.channel.send("언더테일 아시는구나! 혹시 모르시는분들에 대해 설명해드립니다 샌즈랑 언더테일의 세가지 엔딩루트중 몰살엔딩의 최종보스로 진.짜.겁.나.어.렵.습.니.다 공격은 전부다 회피하고 만피가 92인데 샌즈의 공격은 1초당 60이 다는데다가 독뎀까지 추가로 붙어있습니다.. 하지만 이러면 절대로 게임을 깰 수 가없으니 제작진이 치명적인 약점을 만들었죠. 샌즈의 치명적인 약점이 바로 지친다는것입니다. 패턴들을 다 견디고나면 지쳐서 자신의 턴을 유지한채로 잠에듭니다. 하지만 잠이들었을때 창을옮겨서 공격을 시도하고 샌즈는 1차공격은 피하지만 그 후에 바로날아오는 2차 공격을 맞고 죽습니다.")


client.run("NzI2NzYxOTMwODM2MTQ4MjI1.XvmSwQ.-I4XbMep2ISUeLHf8XNY9nI-tMA")

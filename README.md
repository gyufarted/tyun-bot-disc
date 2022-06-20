client.command()
async def displayedmbed():
   embed = discord.Embed(
    title = '',
    description = 'This is a description.',
    colour = discord.Colour.blue()
   )
 
   embed.set_footer(test='This is a footer.')
   embed.set_image(url='')
   embed.set_thumbnail(url='')
   embed.set_author(name='Lacking#6368',
   icon_url='')
   embed.add_field(name='field name', value='Field Value', inline=False)
   embed.add_field(name='field name', value='Field Value', inline=True)
   embed.add_field(name='field name', value='Field Value', inline=True)


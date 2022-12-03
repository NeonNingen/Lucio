```py
from life.species import Human
from skills import python, java, cSharp, other
from datetime import date, time
from random import choices
import existence

class ZainCheema(Human):

    def __init__(self, username='lucio'):
        self.name = f'Zain "{username}" Cheema'
        self.pronouns = ['he' and 'him'],
        self.description = '''
            A university student who uses computer science to keep sane. Lover of software and the
            concepts used to develop our current day hardware. Nothing is out of reach for him, as
            long as he puts his mind to it. 
        '''
        self.aliases = ['Lucio', 'LucioFGC', 'NeonNingen']
        self.skills = {
            'python': [
                python.DiscordPy, python.Tkinter, python.NumPy, python.MatplotLib, python.PyGame, 
                python.PyAutoGui, python.Pkg_resources, python.TensorFlow, python.AzamiDB, 
                python.Lucio
            ],
            'java': [
                java.JavaX.swing, java.Awt, java.Lang, java.Util
            ],
            'cSharp': [
                cSharp.HLSLShader, cSharp.UnityEngine, cSharp.Cake
            ],
            'other': [
                other.ESports, other.Music, other.Weeb
            ]
        }
        self.endpoints = {
            'Discord': {'username': 'LucioFGC', 'discriminator': 0001},
            'Twitter': {'username': 'LucioFGC'}
        }
        self.hobbies = [
            'Programming', 'Gaming', 'Anime/Manga', 'Musician'
        ]
```

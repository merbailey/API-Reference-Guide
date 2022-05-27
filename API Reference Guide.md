---
title: API Reference Guide
permalink: /
layout: default
---

#*API Reference Guide*

##Table of Contents
1. Introduction
2. Sample Code
3. Chapter 2: APIs from A to Z
4. Chapter 3: Reference Material Related to APIs

##Introduction 

Use this *API Reference Guide* to learn about each API that you will use when you create a Python library of APIs.

##Sample Code

Use this sample code as an example of how to write a Python script.

   f ind_champion.

    champion_data = [
     {
       'name': 'ahri',
       'role':  'mid lane',
       'origin': 'vastaya'
     },
     {
       'name': 'teemo',
       'role': 'top lane',
       'origin': 'bandle city'
     },
     {
       'name':'gangplank',
       'role': 'top lane',
       'origin': 'bilgewater'
     },
     {
       'name': 'sona',
       'role': 'support',
       'origin': 'ionia'
     },
     {
       'name': 'miss fortune',
       'role': 'marksman',
       'origin': 'bilgewater'
     }
    ]


    def find_champion(name=None, role=None, origin=None):
     champion_suggestions = []
     for champ in champion_data:
       if name:
         if champ['name'] == name:
           return [champ]
       if role:
         if champ['role'] != role:
           continue
       if origin:
         if champ['origin'] != origin:
           continue
       champion_suggestions.append(champ)
     return champion_suggestions

##Chapter 2: APIs from A to Z
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut sem nulla pharetra diam sit amet nisl suscipit adipiscing. Sagittis aliquam malesuada bibendum arcu vitae elementum. Pulvinar pellentesque habitant morbi tristique senectus et. Diam phasellus vestibulum lorem sed risus. Lacus luctus accumsan tortor posuere ac ut consequat. Hendrerit dolor magna eget est lorem ipsum dolor sit. Nec feugiat in fermentum posuere urna nec. Tortor at risus viverra adipiscing at in tellus integer. Sodales ut eu sem integer vitae justo eget magna fermentum. Eros in cursus turpis massa. Magna eget est lorem ipsum dolor sit. Facilisis sed odio morbi quis commodo odio aenean sed. Amet dictum sit amet justo. Quis lectus nulla at volutpat diam ut venenatis tellus. Nulla pellentesque dignissim enim sit amet venenatis urna cursus. Dui vivamus arcu felis bibendum.

Magna etiam tempor orci eu lobortis elementum nibh. Congue mauris rhoncus aenean vel elit. Magna fringilla urna porttitor rhoncus dolor purus non enim. Porttitor leo a diam sollicitudin tempor id eu. Facilisi cras fermentum odio eu feugiat pretium nibh. Nullam eget felis eget nunc. Netus et malesuada fames ac turpis. Faucibus a pellentesque sit amet porttitor eget dolor morbi. Auctor augue mauris augue neque. Pharetra et ultrices neque ornare aenean. Hendrerit gravida rutrum quisque non tellus orci. Sit amet mauris commodo quis imperdiet massa. Quisque id diam vel quam elementum pulvinar etiam non quam. Tellus pellentesque eu tincidunt tortor aliquam nulla facilisi cras fermentum. Eget magna fermentum iaculis eu non diam. Egestas maecenas pharetra convallis posuere morbi leo urna.

Blandit massa enim nec dui nunc mattis enim ut tellus. Mi eget mauris pharetra et ultrices neque ornare aenean. Massa eget egestas purus viverra accumsan in nisl nisi scelerisque. Interdum velit euismod in pellentesque massa placerat duis. Accumsan sit amet nulla facilisi morbi tempus iaculis urna. Enim eu turpis egestas pretium. Felis eget nunc lobortis mattis aliquam faucibus. Etiam tempor orci eu lobortis elementum nibh tellus. Laoreet suspendisse interdum consectetur libero id faucibus nisl tincidunt. Ipsum dolor sit amet consectetur adipiscing elit duis tristique sollicitudin. Massa sed elementum tempus egestas. Sit amet venenatis urna cursus eget.

##Chapter 3: Reference Material for your API Call Outs
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

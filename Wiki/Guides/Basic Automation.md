<link rel="stylesheet" href="Styles/Stylesheet.css">

<div class="wiki-content">

<a href="Guides Homepage" class="nav-back">← Back to Guides</a>

# Basic Automation

Learn the fundamentals of Create automation - from your first power source to simple contraptions and automation projects.

---

## Overview

Create is the heart of SimplyFellas automation. This guide teaches you the basics of Create mod, from generating your first rotational power to building simple automated systems. Master these fundamentals before moving to advanced automation.

---

## Prerequisites

Before starting this guide, you should:
- Have completed the [Getting Started](Getting-Started) guide
- Have basic resources (wood, stone, iron, andesite)
- Understand basic Minecraft mechanics
- Be familiar with JEI/EMI for recipes

---

## Key Concepts

### Rotational Power

**What is Rotational Power?**
- Create uses rotational force (RPM - Rotations Per Minute) instead of energy
- Power flows through shafts and gearboxes
- Different machines require different RPM and stress (power) levels
- Power can be generated, transferred, and used

**Understanding Stress:**
- Stress is the "power" measurement in Create
- Each generator produces stress units (SU)
- Machines consume stress when operating
- You need enough stress to power all machines

**Understanding RPM:**
- RPM is speed of rotation
- Different machines work best at different RPMs
- Too fast or too slow can cause issues
- Gearboxes and speed controllers adjust RPM

### Power Generation Basics

**Simple Generators:**
- **Waterwheels**: Basic, reliable power from flowing water
- **Windmills**: Free power from wind (requires space)
- **Hand Crank**: Manual power for testing
- **Steam Engines**: Advanced, high-output power (covered in advanced guides)

**Power Transfer:**
- **Shafts**: Basic power transfer
- **Cogwheels**: Change direction and transfer power
- **Gearboxes**: Adjust RPM and stress
- **Clutches**: Enable/disable power flow

---

## Step-by-Step Guides

### Your First Power Source: Waterwheel

**Step 1: Gather Materials**
- 8 Planks (any wood type)
- 8 Sticks
- 1 Andesite Alloy (see recipe in JEI)
- Water source

**Step 2: Craft a Waterwheel**
1. Press `R` on Waterwheel in JEI
2. Craft required materials
3. Craft the Waterwheel

**Step 3: Set Up Waterwheel**
1. Place waterwheel near water source
2. Create water flow (water on both sides)
3. Waterwheel should start spinning
4. Connect a shaft to extract power

**Step 4: Connect Power**
1. Place Shaft next to waterwheel
2. Shaft will start rotating
3. Connect more shafts to extend power
4. Connect machines to use power

**Tips:**
- Waterwheels work best with flowing water on both sides
- More water flow = more power
- Can stack multiple waterwheels
- Reliable early-game power source

### Your First Machine: Millstone

**Step 1: Craft Millstone**
- Press `R` on Millstone in JEI
- Gather required materials
- Craft the Millstone

**Step 2: Set Up Millstone**
1. Place Millstone
2. Connect power from waterwheel
3. Place items in top slot
4. Collect results from bottom

**Step 3: Use Millstone**
- Put wheat in → Get flour out
- Put cobblestone in → Get gravel out
- Many recipes available (check JEI)

**Tips:**
- Millstone needs power to work
- Different items process at different speeds
- Can automate with item input/output
- Essential for many recipes

### Simple Item Processing Setup

**Step 1: Power Generation**
- Set up waterwheel or windmill
- Generate rotational power
- Connect shafts for power transfer

**Step 2: Machine Setup**
- Place processing machine (Millstone, Crushing Wheel, etc.)
- Connect power to machine
- Ensure machine has power

**Step 3: Item Input**
- Manually place items in machine
- Or set up automatic input (funnels, chutes)
- Items process automatically with power

**Step 4: Item Output**
- Collect items from output
- Or set up automatic output
- Use funnels or chutes for automation

**Basic Automation Example:**
```
Waterwheel → Shaft → Millstone
                    ↓
            Input: Wheat
            Output: Flour (auto-collect)
```

---

## Common Builds

### Basic Ore Processing

**Setup:**
1. Power source (waterwheel)
2. Crushing Wheel for ore processing
3. Funnel for item input
4. Chest for output storage

**Process:**
- Ores go into crushing wheel
- Get processed ores out
- Automatically collects in chest
- Simple and effective

### Simple Tree Farm (Manual)

**Setup:**
1. Saw for cutting logs
2. Power source
3. Collection system

**Process:**
- Place logs in saw
- Get planks automatically
- Much faster than manual crafting
- Can be automated further

### Basic Food Processing

**Setup:**
1. Millstone for grinding
2. Mixing basin for combining
3. Power source

**Process:**
- Grind ingredients
- Mix in basin
- Create processed foods
- Foundation for food automation

---

## First Automation Projects

### Project 1: Automated Cobblestone Generator

**Goal:** Automatically generate and process cobblestone

**Steps:**
1. Set up water + lava = cobblestone generator
2. Use mechanical drill to break cobblestone
3. Collect with funnels
4. Process or store automatically

**Benefits:**
- Unlimited cobblestone
- No manual mining needed
- Can process into other materials
- Great learning project

### Project 2: Simple Item Sorter

**Goal:** Automatically sort items into different chests

**Steps:**
1. Set up item input (funnel)
2. Use smart chutes or filters
3. Route items to different chests
4. Organize automatically

**Benefits:**
- Automatic organization
- Saves time
- Keeps base tidy
- Foundation for larger systems

### Project 3: Basic Farm Automation

**Goal:** Automatically harvest and collect crops

**Steps:**
1. Set up mechanical harvester
2. Power the harvester
3. Collect items automatically
4. Store in chests

**Benefits:**
- Automatic food production
- No manual harvesting
- Can expand easily
- Great for food automation

---

## Common Beginner Mistakes

### Mistake 1: Not Enough Power

**Problem:** Machines don't work or work slowly

**Solution:**
- Check stress capacity vs. consumption
- Add more power sources
- Use gearboxes to manage stress
- Check power connections

### Mistake 2: Wrong RPM

**Problem:** Machines work incorrectly or break

**Solution:**
- Check required RPM for machines
- Use gearboxes to adjust speed
- Don't run machines too fast
- Match RPM to machine requirements

### Mistake 3: Poor Power Transfer

**Problem:** Power doesn't reach machines

**Solution:**
- Check shaft connections
- Ensure proper gear alignment
- Use cogwheels for direction changes
- Verify power flow direction

### Mistake 4: Not Using Automation

**Problem:** Manually doing everything

**Solution:**
- Use funnels for input/output
- Automate item collection
- Set up automatic processing
- Let machines do the work

### Mistake 5: Ignoring Recipes

**Problem:** Not knowing what machines do

**Solution:**
- Use JEI to see recipes
- Check machine tooltips
- Experiment with items
- Read Create documentation

---

## Tips & Tricks

### Power Generation Tips

**Waterwheels:**
- More water = more power
- Can stack multiple waterwheels
- Reliable and consistent
- Good for early game

**Windmills:**
- Free power (no fuel)
- Requires space and height
- Variable power (wind dependent)
- Great for mid-game

**Efficiency:**
- Combine multiple power sources
- Use gearboxes to optimize
- Don't waste power on unused machines
- Plan power distribution

### Machine Tips

**Placement:**
- Plan machine layout
- Leave space for expansion
- Organize by function
- Make maintenance easy

**Automation:**
- Automate everything possible
- Use funnels and chutes
- Set up item sorting
- Connect to storage systems

**Optimization:**
- Match RPM to requirements
- Use appropriate power levels
- Organize workflows
- Minimize manual steps

---

## Next Steps

After mastering basic automation:

1. **Advanced Power**: Learn steam engines and diesel generators
2. **Complex Contraptions**: Build more advanced systems
3. **Transportation**: Set up trains and logistics
4. **Advanced Mechanics**: Master complex automation

See [Advanced Mechanics](Advanced-Mechanics) for next steps.

---

## Related Guides

- **[Getting Started](Getting-Started)** - If you haven't completed this yet
- **[Advanced Mechanics](Advanced-Mechanics)** - Next level automation
- **[Power Generation & Management](Power-Generation-&-Management)** - Advanced power
- **[Create Mod Guide](Create)** - Complete Create information

---

## Quest Integration Notes

*When quest systems are added, this guide will be referenced for quests covering basic power generation, simple machines, and first automation projects.*

---

<div class="credits-section">

## About This Guide

This guide provides a comprehensive introduction to Create automation basics. It covers power generation, simple machines, basic contraptions, and first automation projects.

**Last Updated**: Guide is current as of modpack version 1.3.5

</div>

</div>


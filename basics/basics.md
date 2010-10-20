!SLIDE
# Modes
 
!SLIDE bullets incremental
 * insert
 * command
 * select

!SLIDE
# Enter insert mode
## o, i, a, c, s

# Leave insert mode
## esc, ctrl+c

!SLIDE
# IF YOU AREN'T TYPING, YOU SHOULDN'T BE IN INSERT MODE.

!SLIDE smbullets incremental
# Movement

 * h - left
 * j - down
 * k - up
 * l - right
 * arrow keys

!SLIDE
# Command Mode
### Where all of the cool shit happens

!SLIDE smbullets
# such as...
 * delete
 * copy
 * paste
 * sort
 * find and replace
 * collapse lines
 * apply indentation
 * insert many times
 * etc.

!SLIDE command
## Delete
# d modifier

## Copy (yank)
# y modifier

!SLIDE bullets incremental
## possible modifiers:

 * directions
 * numbers
 * characters (`d`, `w`, `$`, `e`)

!SLIDE command
## Paste
# {number} p 

!SLIDE command
# :sort

!SLIDE command
## Find
# /searchstring

## Find and replace
# :%s/find/replace/{modifier}

!SLIDE command
## auto-indentation
# == 
# 10 = j

!SLIDE command
## insert a lot
# 1000 i (type) esc

!SLIDE 
# SELECT MODE!
### byahhhh....

!SLIDE bullets
# Select something

 * `v` - normal
 * `shift v` - line
 * `ctrl v` - block

!SLIDE smbullets
# Then use it

 * yank: `y`
 * delete: `d`
 * insert: `I`, `A`
 * indent: `>`
 * search + replace: `:s/a/b/`


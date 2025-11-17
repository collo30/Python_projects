import pygame
import random
from pygame import mixer
mixer.init()
pygame.init()
surface=pygame.display.set_mode()
gr_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/Screenshot_20230517_191618_Pydroid 3.png")
gr_img_2=pygame.image.load("/storage/emulated/0/DCIM/Download1/Screenshot_20230517_191159_Pydroid 3.png")
gr_img_3=pygame.image.load("/storage/emulated/0/DCIM/Download1/Screenshot_20230517_191438_Pydroid 3.png")
car_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/451d468e-5488-4bf3-88de-c50bcfad6c35.png")
wheel_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/145bec50-5dfa-438b-b4b2-f610285323f6.png")
tree_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/c3cf5bd6-1e17-46c3-9ee8-240ca4ae73eb.png").convert_alpha()
pink_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/ad7d6c31-57c3-4907-b96e-bdb1e4154444.png")
bump_num_ran=0
bump_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/826c3ed8-4eb6-4710-8893-97294b9682de.png").convert_alpha()
bump_img_pos=[-50,940]
bump_img_pos_2=[-50,900]
traff_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/52fd1fe7-15c5-4736-94dc-46a93d1fd195.png")
traff_img_2=pygame.image.load("/storage/emulated/0/DCIM/Download1/bae24da8-926e-47a0-90b2-6cacbaab92b9.png")
traff_img_3=pygame.image.load("/storage/emulated/0/DCIM/Download1/1c3c5d9e-72a9-4165-859c-403dcd12c44f.png")
traff_img_pos=[-50,800]
pole_pos=[-85,800]
pedals_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/35f0ee06-b6d7-497d-9764-50153acf47b7.png")
plus_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/712ba84c-288e-46d8-8899-3f2674d082f9.png")
minus_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/4cb4955b-e6e9-4d2d-a2e5-3729cc2da851.png")
gear_mover=pygame.image.load("/storage/emulated/0/DCIM/Download1/b4a6a286-ba68-4b33-8b77-a26b02b5ef3b.png")
house_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/12bdf7ce-723a-4599-98a2-c775dcaf6f9b.png").convert_alpha()
house_img_2=pygame.image.load("/storage/emulated/0/DCIM/Download1/2d7633a4-2e91-4eec-aece-d896ec08feef.png").convert_alpha()
#house_img_3=pygame.image.load("/storage/emulated/0/Download1/4b725836-1c07-48fd-b1e3-3b514b08923b.png").convert_alpha()
gas_station=pygame.image.load("/storage/emulated/0/DCIM/Download1/46c35896-c9c9-47e7-a8f5-20d1a83cf377.png").convert_alpha()
pas_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/c7a81847-bb0e-4f81-879a-6882946a4322.png")
bump_warn=pygame.image.load("/storage/emulated/0/DCIM/Download1/ab74ec56-3ae1-4cdc-b4a9-2bded718e72b.png")
#traffic_red=pygame.image.load("/storage/emulated/0/Download/52fd1fe7-15c5-4736-94dc-46a93d1fd195.png")
traffic_pole=pygame.image.load("/storage/emulated/0/DCIM/Download1/2e988965-e7f8-41f3-9c99-8f9c3e0a6fcc.png")
gas_sign=pygame.image.load("/storage/emulated/0/DCIM/Download1/00cc76b6-8188-4d96-9f29-bad71c7716e0.png").convert_alpha()
pause_img=pygame.image.load("/storage/emulated/0/DCIM/Download1/8be9d242-d1e9-475e-a7e3-111b0a293b36.png")
gear_a=pygame.Rect((100,1050),(100,100))
gear_b=pygame.Rect((100,1220),(100,100))
gear_cover=pygame.Rect((100,1050),(100,270))
throttle=pygame.Rect((620,1010),(80,180))
brake=pygame.Rect((470,1055),(130,190))
clutch=pygame.Rect((400,1050),(90,200))
pause=pygame.Rect((120,115),(50,50))
instr_box=pygame.Rect((60,110),(600,1200))
#pygame.draw.rect(surface, (0,0,0),pygame.Rect(30, 30, 60, 60),  2,  border_bottom_right_radius=5)
fuel_height=100
fuel_box_height=1330
fuel=pygame.Rect((102,fuel_box_height),(100,fuel_height))
font=pygame.font.Font(None,65)
font_2=pygame.font.Font(None,40)
font_3=pygame.font.Font(None,50)
angle=0
car_rot_angle=0
a=1850
b=1850
c=646
    
n=0
num=0
chg_val=0.09
house_img_pos=[-1100,800]
house_img_pos_2=[-1600,770]
#for r=1
ran_list=[1]
ran_mark=1
tree_img_pos=[-50,770]
tree_img_pos_a=[-200,770]
tree_img_pos_b=[-350,770]
tree_img_pos_c=[-450,770]
tree_img_pos_d=[-550,770]
tree_img_pos_e=[-650,770]
tree_img_pos_f=[-750,770]
tree_img_pos_g=[-900,770]
#bump_img_pos=[-50,940]
###################
tree_img_pos_2=[-100,720]
tree_img_pos_3=[-250,710]
tree_img_pos_4=[-350,690]
tree_img_pos_5=[-550,660]
tree_img_pos_6=[-650,650]
#bump_img_pos_2=[-50,900]
###################
tree_img_pos_7=[-50,905]
fuel_gauge_pos=[100,1410]
n2=1
bump_app_num=0
fuel_use=False
touched=False
gear_1=False
gear_2=False
instr=False
prev_n=0
gear_val=3
num_show=("D1")
bump_show=("bump")
val=0
grav_rev_val=0.01
ran_num=0
scene_num=0
scene_mark=1
bump_num=0
n_red=False
scene_list=[1]
gear_mover_pos=[100,1140]
car_pos=[600,700]
colour=(0,200,0)
#red=(230,0,0)
#gear_val_text=font.render(num_show,True,black,None)
fuel_num=0
fuel_num_2=0
gas_pos=-1000
mixer.music.set_volume(0.5)
money=1000
bump_warn_val=0
pas_aboard=True
pas_val=0
fare_list=[]
fuel_need=0
fuel_need_val=0
pas_hap=10
pas_no=5
fare=0
bump_mult_val=0
traff_red=False
traff_amber=False
traff_green=False
traff_break=False
pena_val=0
money_text_pos=[490,120]

gas_corr_val=0
x=0
while True:
    if fuel_use==True:
        fuel_gauge_pos[1]+=0.01
    if fuel_gauge_pos[1]>1417:
        touched=False
        fuel_gauge_pos[1]=1417
    if fuel_gauge_pos[1]>1410:
        fuel_num=1
    if gas_pos>1000 and fuel_num_2==0:
        gas_pos=-1000
        #fuel_num=0
    if gas_pos>180 and gas_pos<280:
            gas_corr_val=1
            if n==0:
                if gear_val==2 and val==1:
                    fuel_num_2=1
                    if fuel_need_val==0:
                        fuel_need=random.randint(1320,1400)
                        #fare=(1417-fuel_gauge_pos[1])+50
                
                        fuel_need_val=1
                    if fuel_gauge_pos[1]>fuel_need:
                        fuel_gauge_pos[1]-=1
                        money-=1
                        if pas_val==0:
                            pas_aboard=True
                        if pas_val>0:
                            pas_aboard=False
                    if fuel_gauge_pos[1]<fuel_need:
                        fuel_gauge_pos[1]=fuel_need
                        pas_aboard=True
                        fare=((1417-fuel_gauge_pos[1])/5)+10
                        fare_list.append(fare*pas_no)
                        if pas_val>0:
                            le=len(fare_list)
                            cur_fare=fare_list[le-2]
                            money=cur_fare+money
                        pas_val=pas_val+1
                        #fuel_need_val=0
       
    if gas_pos>1000 and fuel_num_2==1:
        gas_pos=-1000
        fuel_num=0
        fuel_num_2=0
        fuel_need_val=0                   
    if fuel_gauge_pos[1]<1400 and fuel_num_2==0:
            fuel_num=0
            
        
        
    #pygame.mixer.music.play(-1)
    if gas_pos>280:
        gas_corr_val=0
    gear_val_text=font.render(num_show,
    True,colour,None)
    full_fuel_text=font_2.render("_______F",True,(0,200,0),None)
    empty_fuel_text=font_2.render("_______E",True,(200,0,0),None)
    gear_instr=font_2.render("Tap + on the left to shift gear UP",True,(200,200,0),None)
    gear_instr_2=font_2.render("Tap - on the left to shift gear DOWN",True,(200,200,0),None)
    gear_instr_3=font_2.render("A full trip starts & ends at terminus",True,(200,200,0),None)
    gear_instr_4=font_2.render("Completing a trip earns you money",True,(200,200,0),None)
    gear_instr_5=font_2.render("Fueling for a trip costs you money",True,(200,200,0),None)
    gear_instr_6=font_2.render("Fuel on seeing fuel sign",True,(200,200,0),None)
    gear_instr_7=font_2.render("To fuel;engage neutral (N) & hold brake",True,(200,200,0),None)
    fuel_gauge=font_2.render("------------",True,(100,100,50),None)
    money_text=font.render(str(money),True,(250,200,0),None)
    mi_val=280+(n/1)
    ran_text=font.render(str(mi_val),True,(200,0,0),None)
    dollar_sign=font.render("$",True,(250,200,0),None)
    #surface.fill((0,0,0),throttle)
    #pygame.mixer.music.play(-1)
    for ev in pygame.event.get():
        if ev.type==pygame.QUIT:
            pygame.quit()
        if ev.type==pygame.MOUSEBUTTONDOWN:
            #pygame.mixer.music.stop()
            if instr==True:
                instr=False
                n=prev_n
            if pause.collidepoint(ev.pos) and instr==False:
                prev_n=n
                instr=True
            if throttle.collidepoint(ev.pos):
                touched=True
                val=0
                fuel_use=True
            if gear_a.collidepoint(ev.pos) and gear_val<8:
                gear_1=True
            if gear_b.collidepoint(ev.pos) and gear_val>1:
                gear_2=True
            if brake.collidepoint(ev.pos):
                val=1
                touched=False
        if ev.type==pygame.MOUSEBUTTONUP:
            #pygame.mixer.music.play(-1)
            touched=False
            fuel_use=False
            val=0
    if instr==True:
        n=0  
    ran_num+=(n/10)
    if ran_num>5000 and fuel_num==0:
        if n>20:
            ran=random.randint(1,3)
            ran_list.append(ran)
            ran_mark+=1
            ran_num=0
    if ran_num>10 and fuel_num==1:
        ran=random.randint(1,1)
        ran_list.append(ran)
        ran_mark+=1
        ran_num=0
    r=(ran_list[ran_mark-1])
    scene_num+=0.5
    if scene_num>100:
        scene_ran=random.randint(1,1)
        scene_list.append(scene_ran)
        scene_mark+=1
        scene_num=0
    scene_r=(scene_list[scene_mark-1])
    if bump_mult_val==0:
        bump_num_ran=random.randint(1,10)
        bump_mult_val=1
    bump_ran=n*bump_num_ran
    bump_num+=bump_ran
    if bump_num<45000 and r==2:
        bump_warn_val=0
    if bump_num>45000 and r==2:
        bump_warn_val=0
    if bump_num<90000 and r==1:
        bump_warn_val=0
    if bump_num>90000 and r==1:
        bump_warn_val=1
    if bump_num>100000 and r==1:
        traff_img_pos[0]+=n
        pole_pos[0]+=n
        if traff_img_pos[0]>800:
                traff_img_pos[0]=-50
                pole_pos[0]=-90
                bump_num=0
                bump_mult_val=0
        if traff_img_pos[0]>280 and traff_img_pos[0]<(280+(n/1)):
            if traff_red==True:
                traff_break=True
        if traff_img_pos[0]>280 and traff_img_pos[0]<(280+(n/1)):
            if traff_amber==True:
                traff_break=True
    if traff_break==True:
                    if pena_val<300:
                        money=money-1
                        pena_val+=5
                        if money_text_pos[1]>60:
                            money_text_pos[1]-=5
                        if money_text_pos[1]==60:
                            money_text_pos[1]=180
                        
    if pena_val==300:
             traff_break=False
             pena_val=0
             money_text_pos[1]=120
    if traff_img_pos[0]>0 and r==1:
                x+=0.5
                if x<50 and x>0:
                    traff_red=True
                    traff_amber=False
                    traff_green=False
                if x>50 and x<100:
                 traff_red=False
                 traff_amber=True
                 traff_green=False
                if x>100 and x<190:
                 traff_red=False
                 traff_amber=False
                 traff_green=True
                if x>190:
                 x=1
                 
                
                 
                 
    if bump_img_pos[0]>390 and r==1:
                if a>1842:
                    a=a-6
                    car_pos[1]=900
                    car_rot_angle+=2
                if bump_img_pos[0]>410:
                    a=1850
                    car_rot_angle=0
    if bump_num>50000 and r==2:
        ##b=1910
        bump_img_pos_2[0]+=n
        bump_img_pos_2[1]+=(n/7.6)
        if bump_img_pos_2[0]>800:
            bump_img_pos_2[0]=-50
            bump_img_pos_2[1]=900
            bump_num=0
            bump_mult_val=0
        if  bump_img_pos_2[0]>290 and r==2:
            if b>1866:
                b=b-2
                #car_pos[1]=900
                car_rot_angle-=2
        if bump_img_pos_2[0]>310 and r==2:
                 b=1876
                 car_rot_angle=-10
        if bump_img_pos_2[0]>450 and r==2:
                 if a>1900:
                     a=a-2
                     car_rot_angle+=2
        if bump_img_pos_2[0]>470 and r==2:
                     a=1910
                     car_rot_angle=-10
                     
                 
                 
                 
            
            
        
    if gear_1==True:
        gear_mover_pos[1]-=15
        if gear_mover_pos[1]<1040:
                gear_val+=1
                gear_mover_pos[1]=1145
                gear_1=False
    if gear_2==True:
        gear_mover_pos[1]+=15
        if gear_mover_pos[1]>1240:
                gear_val-=1
                gear_mover_pos[1]=1145
                gear_2=False
    if gear_val==1:
        if r==1:
            chg_val=-0.04
        if r==2:
            chg_val=-0.08
        if r==3:
            chg_val=-0.03
        num_show=("R")
        colour=(0,200,0)
    if gear_val==2:
        chg_val=0
        num_show=("N")
        colour=(0,200,0)
    if  gear_val==3:
         num_show=("D1")
         if n>20:
             chg_val=0.02
             colour=(200,0,0)
         else:
             chg_val=0.09
             colour=(0,200,0)
    if gear_val==4:
         num_show=("D2")
         if n>60:
             chg_val=0.02
             colour=(200,0,0)
         if n>20 and n<60:
             chg_val=0.09
             colour=(0,200,0)
         if n<20:
             chg_val=0.04
             colour=(200,0,0)
    if gear_val==5:
         num_show=("D3")
         if n>100:
             chg_val=0.02
             colour=(200,0,0)
         if n>60 and n<100:
             chg_val=0.09
             colour=(0,200,0)
         if n<60:
             chg_val=0.03
             colour=(200,0,0)
    if gear_val==6:
         num_show=("D4")
         if n>150:
             chg_val=0.02
             colour=(200,0,0)
         if n>100 and n<150:
             chg_val=0.09
             colour=(0,200,0)
         if n<100:
             chg_val=0.02
             colour=(200,0,0)
    if gear_val==7:
         num_show=("D5")
         if n>190:
             chg_val=0.02
             colour=(200,0,0)
         if n>100 and n<190:
             chg_val=0.09
             colour=(0,200,0)
         if n<100:
             chg_val=0.02
             colour=(200,0,0)
    if gear_val==8:
         num_show=("D6")
         if n>250:
             chg_val=0.02
             colour=(200,0,0)
         if n>190 and n<250:
             chg_val=0.09
             colour=(0,200,0)
         if n<190:
             chg_val=0.02
             colour=(200,0,0)
    #surface.blit(gr_img,(0,0))
    wheel_rot_img=pygame.transform.rotate(wheel_img,angle)
    wheel_rot_img_2=pygame.transform.rotate(wheel_img,angle)
    car_rot_img=pygame.transform.rotate(car_img,car_rot_angle)
    cent=wheel_rot_img.get_rect()
    pos_rot=((895-cent.height)/2,(a-cent.width)/2)
    pos_rot_2=((c-cent.height)/2,(b-cent.width)/2)
    car_cent=car_img.get_rect()
    car_pos_rot=((car_pos[0]-car_cent.height)/2,(car_pos[1]-car_cent.width)/2)
    if r==1:
        surface.blit(gr_img,(0,0))
        if scene_r==1:
            if fuel_num==0:
                surface.blit(house_img,house_img_pos)
                surface.blit(house_img_2,house_img_pos_2)
            surface.blit(tree_img,tree_img_pos)
            surface.blit(tree_img,tree_img_pos_a)
            surface.blit(tree_img,tree_img_pos_b)
            surface.blit(tree_img,tree_img_pos_c)
            surface.blit(tree_img,tree_img_pos_d)
            surface.blit(tree_img,tree_img_pos_e)
            surface.blit(tree_img,tree_img_pos_f)
            surface.blit(tree_img,tree_img_pos_g)
        if fuel_num==1:
            surface.blit(gas_station,(gas_pos,720))
        surface.blit(traffic_pole,pole_pos)
        if traff_red==True:
            surface.blit(traff_img,traff_img_pos)
        if traff_amber==True:
            surface.blit(traff_img_2,traff_img_pos)
        if traff_green==True:
            surface.blit(traff_img_3,traff_img_pos)
        surface.blit(car_rot_img,(270,822))
        a=1850
        b=1850
        surface.blit(wheel_rot_img,(pos_rot))
        surface.blit(wheel_rot_img_2,
        (pos_rot_2))
        angle=angle+n
        if val==1 and n>0:
            n=n-(n/15)
        if touched==True:
            n=n+chg_val
            num=num+0.05
            scene_num+=1
        if touched==False:
            if n>0:
                n=n-0.05
                if (n-0.05)<0:
                    n=n-n
            if n<0:
                 n=n+0.05
                 if (n+0.05)>0:
                    n=0
                    
                    
             
                    
                    
  
                #num=num-0.05
        car_rot_angle=0
        tree_img_pos[0]+=n
        tree_img_pos_a[0]+=n
        tree_img_pos_b[0]+=n
        tree_img_pos_c[0]+=n
        tree_img_pos_d[0]+=n
        tree_img_pos_e[0]+=n
        tree_img_pos_f[0]+=n
        tree_img_pos_g[0]+=n
        if fuel_num==0:
            house_img_pos[0]+=n
            house_img_pos_2[0]+=n
        if fuel_num==1:
            gas_pos+=n
        #house_img_pos_3[0]+=n
        #if house_img_pos_3[0]>200:
            #surface.blit(house_img_3,(house_img_pos[0]-200,505))
        if house_img_pos[0]>800 and n>0:
            tree_img_pos[0]=0
            tree_img_pos_a[0]=-200
            tree_img_pos_b[0]=-350
            tree_img_pos_c[0]=-450
            tree_img_pos_d[0]=-550
            tree_img_pos_e[0]=-650
            tree_img_pos_f[0]=-750
            tree_img_pos_g[0]=-900
            house_img_pos[0]=-1100
            if house_img_pos_2[0]>800:
                house_img_pos_2[0]=-1600
        if house_img_pos[0]<-2000 and n<0:
             tree_img_pos[0]=2000
             tree_img_pos_a[0]=1900
             tree_img_pos_b[0]=1800
             tree_img_pos_c[0]=1700
             tree_img_pos_d[0]=1600
             tree_img_pos_e[0]=1500
             tree_img_pos_f[0]=1400
             tree_img_pos_g[0]=1300
             house_img_pos[0]=1200
             house_img_pos_2[0]=600
             
    if r==2:
         if val==1 and n>0:
             n=n-(n/30)
             if (n-(n/30))<0:
                 n=0
         if val==1 and n<0:
             if n<0:
                 n=n-(n/50)
                 if (n-(n/50))>0:
                     n=0
         if touched==True:
             n=n+chg_val
             num=num+0.05
         if touched==False and val==0:
             n=n-0.1
         #surface.blit(tree_img,(300,600))
         
         surface.blit(gr_img_2,(0,0))
         surface.blit(bump_img,bump_img_pos_2)
         surface.blit(pink_img,tree_img_pos_2)
         surface.blit(pink_img,tree_img_pos_3)
         surface.blit(pink_img,tree_img_pos_4)
         surface.blit(pink_img,tree_img_pos_5)
         surface.blit(pink_img,tree_img_pos_6)
         surface.blit(car_rot_img,(270,825))
         car_rot_angle=-10
         a=1910
         b=1876
         c=654
         surface.blit(wheel_rot_img,(pos_rot))
         surface.blit(wheel_rot_img_2,(pos_rot_2))
         angle=angle+n
         n2=(n/7.6)
         tree_img_pos_2[0]+=n
         tree_img_pos_2[1]+=n2
         tree_img_pos_3[0]+=n
         tree_img_pos_3[1]+=n2
         tree_img_pos_4[0]+=n
         tree_img_pos_4[1]+=n2
         tree_img_pos_5[0]+=n
         tree_img_pos_5[1]+=n2
         tree_img_pos_6[0]+=n
         tree_img_pos_6[1]+=n2
         if tree_img_pos_6[0]>850 and n>0:
             #tree_img_pos_2=[-100,720]
#tree_img_pos_3=[-250,710]
#tree_img_pos_4=[-350,690]
#tree_img_pos_5=[-550,660]
#tree_img_pos_6=[-650,660]
             tree_img_pos_2[0]=-100
             tree_img_pos_2[1]=720
             tree_img_pos_3[0]=-250
             tree_img_pos_3[1]=710
             tree_img_pos_4[0]=-350
             tree_img_pos_4[1]=690
             tree_img_pos_5[0]=-550
             tree_img_pos_5[1]=660
             tree_img_pos_6[0]=-650
             tree_img_pos_6[1]=650
         if tree_img_pos_6[0]<-500 and n<0:
              tree_img_pos_2[0]=1200
              tree_img_pos_2[1]=890
              tree_img_pos_3[0]=1300
              tree_img_pos_3[1]=910
              tree_img_pos_4[0]=1400
              tree_img_pos_4[1]=920
              tree_img_pos_5[0]=1500
              tree_img_pos_5[1]=925
              tree_img_pos_6[0]=1600
              tree_img_pos_6[1]=935
              
              
    if r==3:
          #tree_img_pos_3=[-50,905]
          if val==1 and n>0:
              if n<10 and n>0:
                  brk_val=0.2
              if n<20 and n>10:
                  brk_val=0.3
              if n>20 and n<50:
                  brk_val=0.5
              if n>50 and n<100:
                  brk_val=0.7
              if n>100:
                  brk_val=1.2
              if n<0:
                  brk_val=3
              n=n-brk_val
              if (n-brk_val)<0:
                  n=n-n
          if touched==True:
                 n=n+chg_val
          if touched==False:
                 n=n+0.02
          surface.blit(gr_img_3,(0,0))
          surface.blit(tree_img,(tree_img_pos_7))
          surface.blit(car_rot_img,(255,880))
          car_rot_angle=10
          a=1985
          b=2025
          c=654
          surface.blit(wheel_rot_img,(pos_rot))
          surface.blit(wheel_rot_img_2,(pos_rot_2))
          angle=angle+n
          n2=(n/5.6)
          tree_img_pos_7[0]+=n
          tree_img_pos_7[1]-=n2
          if tree_img_pos_7[0]>800 and n>0:
             tree_img_pos_7[0]=-50
             tree_img_pos_7[1]=905
          if n<0 and tree_img_pos_7[0]<-200:
             tree_img_pos_7[0]=800
             tree_img_pos_7[1]=750
          
    #surface.blit(pedals_img,(300,1000))        
    surface.fill((80,50,30),brake)    
    surface.fill((80,50,30),throttle)#80,50,30
    surface.blit(pedals_img,(500,1000))
    surface.fill((80,45,30),clutch)
    surface.fill((125,125,125),gear_a)
    surface.fill((125,125,125),gear_b)
    surface.fill((125,125,125),gear_cover)
    surface.fill((220,220,220),fuel)
    surface.blit(full_fuel_text,(100,1305))
    surface.blit(empty_fuel_text,(100,1405))
    surface.blit(fuel_gauge,fuel_gauge_pos)
    surface.blit(plus_img,(100,1050))
    surface.blit(minus_img,(110,1230))
    surface.blit(gear_mover,(gear_mover_pos))
    surface.blit(gear_val_text,(128,1170))
    #surface.blit(money_text,(500,100))
    #surface.blit(dollar_sign,(475,100))
    if bump_warn_val==1 and r<3:
        surface.blit(bump_warn,(500,400))
    if pas_aboard==False and r==1:
        surface.blit(pas_img,(332,840))
    if pas_aboard==True and r==1:
        surface.blit(pas_img,(332,840))
        surface.blit(pas_img,(380,840))
        surface.blit(pas_img,(440,840))
    if pas_aboard==True and r==2:
        surface.blit(pas_img,(339,850))
        surface.blit(pas_img,(395,862))
        surface.blit(pas_img,(452,872))
    if pas_aboard==True and r==3:
        surface.blit(pas_img,(320,920))
        surface.blit(pas_img,(372,912))
        surface.blit(pas_img,(429,905))
    #surface.blit(ran_text,(400,400))
    if gas_corr_val==1 and fuel_num==1:
        surface.blit(gas_sign,(350,550))
    #surface.blit(traffic_pole,pole_pos)
    #surface.blit(traffic_red,(400,600))
    #surface.fill((0,0,0),black_rect)
    pygame.draw.rect(surface, (0,0,0),pygame.Rect(110, 100, 495,80),  40,border_bottom_right_radius=30,border_top_right_radius=30,border_bottom_left_radius=30,border_top_left_radius=30)
    surface.blit(money_text,money_text_pos)
    pygame.draw.rect(surface, (173,216,230),pygame.Rect(0,15, 1150,250), 165,border_bottom_right_radius=0,border_top_right_radius=0,border_bottom_left_radius=0,border_top_left_radius=0)
    surface.blit(dollar_sign,(465,120))
    surface.fill((200,200,200),pause)
    surface.blit(pause_img,(120,115))
    if instr==True:
        surface.fill((0,0,0),instr_box)
        surface.blit(gear_instr,(100,150))
        surface.blit(gear_instr_2,(100,200))
        surface.blit(gear_instr_3,(100,250))
        surface.blit(gear_instr_4,(100,300))
        surface.blit(gear_instr_5,(100,350))
        surface.blit(gear_instr_6,(100,400))
        surface.blit(gear_instr_7,(100,450))
        
        
    pygame.display.flip()

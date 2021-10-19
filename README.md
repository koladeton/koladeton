a ={ 'машина1':'1', 'машина2':'2', 'машина3':'3', 'машина4':'4','машина5':'5','машина6':'6', 'машина7':'7','машина8':8,'машина9':9,'машина10':10}

import cv2
d = input('введите название машины')

if a[d] == '1':
    img = cv2.imread('image/dominik-toretto.jpg')
    cv2.imshow('машина1', img)
    cv2.waitKey(0)

elif a[d] == '2':
    img = cv2.imread('image/pops.jpg')
    cv2.imshow('машина2', img)
    cv2.waitKey(0)

elif a[d] == '3':
    img = cv2.imread('image/4411.jpg')
    cv2.imshow('машина3', img)
    cv2.waitKey(0)

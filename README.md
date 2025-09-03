import pygame
import randint 

pygame.init()

#setting up the game window
window_width = 800
window_height = 600
window = pygame.display.set_mode((window_width, window_height))
pygame.display.set_caption("Snake Game")

white = (255,255 255)
black = (0. 0, 0)
red = (255, 0, 0)
game_over = False
score = 0

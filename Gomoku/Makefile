# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: Zexi Wang <twopieces0921@gmail.com>        +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/04/07 12:53:24 by Zexi Wang         #+#    #+#              #
#    Updated: 2019/04/11 20:41:53 by Zexi Wang        ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = gomoku
CC = gcc 

SRCS = srcs/init.c srcs/util.c srcs/count.c srcs/mode.c srcs/eval.c srcs/form.c
INCS = -I incs -I libs/libft/incs
LIBS = libs/libft/libft.a

all: $(NAME)

$(NAME):
	@$(CC) -o $(NAME) $(SRCS) $(INCS) $(LIBS)

fclean:
	@rm -rf $(NAME)

re: fclean all

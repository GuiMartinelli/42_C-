# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: guferrei <guferrei@student.42sp.org.br>    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/06/02 20:47:54 by guferrei          #+#    #+#              #
#    Updated: 2022/06/02 20:49:13 by guferrei         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME=iter

CC=c++

CCFLAGS=-Wall -Wextra -Werror -std=c++98

FILE=main.cpp

all: $(NAME)

$(NAME): $(FILE)
	$(CC) $(CCFLAGS) $(FILE) -o $(NAME)

clean:
	rm $(NAME)

fclean: clean

re: clean all

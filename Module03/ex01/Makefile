# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: guferrei <guferrei@student.42sp.org.br>    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/05/19 19:04:57 by guferrei          #+#    #+#              #
#    Updated: 2022/05/19 20:02:38 by guferrei         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME=ScavTrap

CC=c++

CCFLAGS=-Wall -Wextra -Werror -std=c++98

FILES=ClapTrap.cpp ScavTrap.cpp main.cpp

all: $(NAME)

$(NAME): $(FILES)
	$(CC) $(CCFLAGS) $(FILES) -o $(NAME)

clean:
	rm $(NAME)

fclean: clean

re: clean all

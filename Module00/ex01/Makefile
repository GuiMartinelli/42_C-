# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: guferrei <guferrei@student.42sp.org.br>    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/05/02 15:15:01 by guferrei          #+#    #+#              #
#    Updated: 2022/05/05 17:58:24 by guferrei         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME=phonebook

CC=c++

CCFLAGS= -Wall -Wextra -Werror -std=c++98

FILES=Contact.cpp PhoneBook.cpp main.cpp

all: $(NAME)

$(NAME): $(FILES)
	$(CC) $(CCFLAGS) $(FILES) -o $(NAME)

clean:
	rm $(NAME)

fclean: clean
	rm $(NAME)

re: clean all

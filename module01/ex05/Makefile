# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: sgath <sgath@student.42.fr>                +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2021/05/20 11:15:19 by sgath             #+#    #+#              #
#    Updated: 2021/05/21 17:15:48 by sgath            ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

SRCS =		main.cpp \
			Brain.cpp \
			Human.cpp \

INCLUDES =	Brain.hpp \
			Human.hpp \

NAME =		Hi_Brain

FLAGS =		-Wall -Wextra -Werror

.PHONY: 	all clean fclean re

all: 		$(NAME)

$(NAME):	 $(INCLUDES) $(SRCS)
			clang++ $(SRCS) $(FLAGS) -o $@

clean:
			rm -rf *.o

fclean:		clean
			rm -rf $(NAME)

re:			fclean all

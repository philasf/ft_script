# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: passef <passef@student.42.fr>              +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2017/04/21 14:58:27 by passef            #+#    #+#              #
#    Updated: 2018/02/09 14:21:17 by passef           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME =	libft.a

SRC =	ft_memccpy.c \
		ft_memchr.c	\
		ft_memcmp.c	\
		ft_memcpy.c	\
		ft_memdel.c	\
		ft_memmove.c \
		ft_memset.c	\
		ft_memalloc.c \
		ft_bzero.c \
		ft_strisalpha.c \
		ft_strisnum.c \
		ft_strisalnum.c \
		ft_strisprint.c \
		ft_strnew.c \
		ft_strequ.c	\
		ft_striter.c \
		ft_strnstr.c \
		ft_strsub.c \
		ft_strjoin.c \
		ft_strrchr.c \
		ft_strcat.c	\
		ft_strlcat.c \
		ft_strsplit.c \
		ft_strstr.c \
		ft_strclr.c \
		ft_strmap.c	\
		ft_strtrim.c \
		ft_strcmp.c \
		ft_strmapi.c \
		ft_strcpy.c	\
		ft_strncpy.c \
		ft_strncat.c \
		ft_strdel.c	\
		ft_strncmp.c \
		ft_strdup.c	\
		ft_strnequ.c \
		ft_strrev.c \
		ft_striteri.c \
		ft_strchr.c	\
		ft_strlen.c \
		ft_size_bin.c \
		ft_atoi.c \
		ft_itoa.c \
		ft_utoa.c \
		ft_llutoa.c \
		ft_lltoa.c \
		ft_itoa_base.c \
		ft_ltoa_base.c \
		ft_ftoa.c \
		ft_lftoa.c \
		ft_isalnum.c \
		ft_isalpha.c \
		ft_isascii.c \
		ft_isdigit.c \
		ft_isprint.c \
		ft_tolower.c \
		ft_toupper.c \
		ft_putnbr.c	\
		ft_putnbr_fd.c \
		ft_putstr.c	\
		ft_putstr_fd.c \
		ft_putchar.c \
		ft_putchar_fd.c	\
		ft_putendl_fd.c \
		ft_putendl.c \
		ft_lstnew.c \
		ft_lstdelone.c \
		ft_lstdel.c \
		ft_lstadd.c \
		ft_lstaddend.c \
		ft_lstiter.c \
		ft_lstmap.c \
		ft_lstsize.c \
		ft_lstcat.c \
		ft_lstjoin.c \
		ft_lstfind.c \
		ft_lstrev.c \
		ft_lstclr.c \
		ft_get_next_line.c \
		ft_swap.c \
		ft_puterror.c  \

OBJ	=	$(SRC:.c=.o)
CC	= gcc
FLAGS = -Wall -Werror -Wextra -g -O0
RM = rm -rf
CG = \033[92m
CY = \033[95m
CE = \033[0m

all	: $(NAME)
$(NAME)	: $(OBJ)
	@echo "\033[K$(CY)[LIBFT] :$(CE) $(CG)Creating Library$(CE) \033[1A";
	@ar rc $(NAME) $(OBJ)
	@ranlib $(NAME)
	@echo "\033[K$(CY)[LIBFT] : $(CE) $(CG)LIBFT Compiled!$(CE)";

%.o: %.c
	@$(CC) $(FLAGS) -c $< -o $@
	@echo "\033[K$(CY)[LIBFT] :$(CE) $(CG) Compiling $<$(CE) \033[1A";

clean	: 
	@$(RM) $(OBJ)

fclean	: clean
	@$(RM) $(NAME)
	@echo "\033[K$(CY)[LIBFT] : $(CE) $(CG)Cleaning Library$(CE)";

re		: fclean all

# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: rcotter- <rcotter-@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/09/03 19:09:28 by drdraugr          #+#    #+#              #
#    Updated: 2019/09/15 17:08:04 by rcotter-         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a
SRC = ft_atoi.c ft_bzero.c ft_isalnum.c ft_isalpha.c ft_isascii.c ft_isdigit.c \
ft_isprint.c ft_itoa.c ft_lstadd.c ft_lstappend.c ft_lstdel.c ft_lstdelone.c \
ft_lstiter.c ft_lstmap.c ft_lstnew.c ft_memalloc.c ft_memccpy.c \
ft_memchr.c ft_memcmp.c ft_memcpy.c ft_memdel.c ft_memmove.c ft_memset.c \
ft_putchar.c ft_putchar_fd.c ft_putendl.c ft_putendl_fd.c ft_putnbr.c \
ft_putnbr_fd.c ft_putstr.c ft_putstr_fd.c ft_strcat.c ft_strchr.c \
ft_strclr.c ft_strcmp.c ft_strcpy.c ft_strdel.c ft_strdup.c ft_strequ.c \
ft_striter.c ft_striteri.c ft_strjoin.c ft_strlcat.c ft_strlen.c \
ft_strmap.c ft_strmapi.c ft_strncat.c ft_strncmp.c ft_strncpy.c ft_strnequ.c \
ft_strnew.c ft_strnstr.c ft_strrchr.c ft_strsplit.c ft_strstr.c ft_strsub.c \
ft_strtrim.c ft_tolower.c ft_toupper.c ft_sqrt.c ft_lstlen.c ft_isspace.c ft_octal.c\
ft_latoi.c ft_hex.c ft_to_char.c ft_expn.c ft_unitoa.c ft_float_itoa.c \
ft_chrstr.c ft_rewrite.c ft_addchr_e.c ft_addchr_s.c ft_comb.c get_next_line.c\
ft_chr_rep.c ft_addnchr_e.c ft_addnchr_s.c ft_makemtrx.c ft_upstr.c ft_lowstr.c  ft_strcpy_chr.c\
ft_pow.c ft_strojoin.c ft_swap.c ft_hex_dec.c ft_atoi_base.c ft_len_nbr.c ft_bin_dec.c\

CC		:= gcc
CFLAGS	:= -Wall -Wextra -Werror
OBJ = $(SRC:.c=.o)
INC = libft.h

all: $(NAME)

$(NAME): $(OBJ)
	gcc $(CFLAGS) -c $(SRC) -I$(INC)
	ar rc $(NAME) $(OBJ) 
	ranlib $(NAME)
%.o: %.c
	$(CC) $(CFLAGS) -o $@ -c $<
clean:
	/bin/rm -f $(OBJ)

fclean: clean
	/bin/rm -f $(NAME)

re: fclean all

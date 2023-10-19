In this project, I practiced building and using singly linked lists in C while learning when and why to use linked lists versus arrays. Below are the files and prototype



a. struct list_s: This include; char *str, unsigned int len, struct list_s *next


b. typedef list_t : struct list_s

c. 0-print_list.c: size_t print_list(const list_t *h);

d. 1-list_len.c: size_t list_len(const list_t *h);

e. 2-add_node.c: list_t *add_node(list_t **head, const char *str);


f. 3-add_node_end.c:  list_t *add_node_end(list_t **head, const char *str);



4-free_list.c:  void free_list(list_t *head)

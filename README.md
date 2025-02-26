```c
typedef struct {
	char *name;
	int age;
	char *fun_fact;
} User;

int main(int argc, char *argv[])
{
	User me = {};

	me.name = "Marouane Souiri";
	me.age = 18;
	me.fun_fact = "5rdala is a high quality weed in morroco";

	return 0;
}
```

[TOC]

```
ctype.h
errno.h
fcntl.h
fenv.h
inttypes.h
local.h
pthread.h
sched.h
semaphore.h
setjmp.h
signal.h
stdarg.h
stdio.h
stdlib.h
string.h
mman.h
uname.h
time.h
unistd.h
```

```
assert.h
complex.h
ctype.h
errno.h
fenv.h
float.h
inttypes.h
limits.h
locale.h
math.h
setjmp.h
signal.h
stdalign.h
stdarg.h
stdatomic.h
stdbool.h
stddef.h
stdint.h
stdio.h
stdlib.h
string.h
time.h
Version.h
wchar.h
wctype.h
xlocale.h
__libc.h
```

1. **输入/输出（I/O）**：
   - stdio.h
   - fcntl.h
2. **错误处理**：
   - errno.h
3. **字符处理**：
   - ctype.h
   - string.h
4. **内存管理**：
   - stdlib.h
   - mman.h
5. **时间和日期**：
   - time.h
6. **线程和进程**：
   - pthread.h
   - sched.h
   - semaphore.h
   - signal.h
   - setjmp.h
   - unistd.h
7. **数值处理**：
   - inttypes.h
8. **可变参数**：
   - stdarg.h
9. **环境变量**：
   - fenv.h
   - uname.h

### ctype.h

|      |                                                              |      |      |
| ---- | ------------------------------------------------------------ | ---- | ---- |
|      | [isalnum()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/isalnum.html) | *    | *    |
|      | [isalpha()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/isalpha.html) | *    | *    |
|      | [isblank()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/isblank.html) | *    | *    |
|      | [iscntrl()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/iscntrl.html) | *    | *    |
|      | [isdigit()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/isdigit.html) | *    | *    |
|      | [isgraph()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/isgraph.html) | *    | *    |
|      | [islower()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/islower.html) | *    | *    |
|      | [isprint()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/isprint.html) | *    | *    |
|      | [ispunct()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/ispunct.html) | *    | *    |
|      | [isspace()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/isspace.html) | *    | *    |
|      | [isupper()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/isupper.html) | *    | *    |
|      | [isxdigit()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/isxdigit.html) | *    | *    |
|      | [tolower()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/tolower.html) | *    | *    |
|      | [toupper()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/toupper.html) | *    | *    |

### errno.h


| [<errno.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/errno.h.html) |                                                              |      |      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | ---- |
|                                                              | [errno](https://pubs.opengroup.org/onlinepubs/9699919799/functions/errno.html) | *    |      |



### fcntl.h

| [<fcntl.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/fcntl.h.html) |                                                              |      |      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | ---- |
|                                                              | [open()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/open.html) | *    |      |
### fenv.h

| [<fenv.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/fenv.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [feclearexcept()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/feclearexcept.html) | *    |      |
|                                                              | [fegetenv()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fegetenv.html) | *    |      |
|                                                              | [fegetexceptflag()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fegetexceptflag.html) | *    |      |
|                                                              | [fegetround()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fegetround.html) | *    |      |
|                                                              | [feholdexcept()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/feholdexcept.html) | *    |      |
|                                                              | [feraiseexcept()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/feraiseexcept.html) | *    |      |
|                                                              | [fesetenv()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fesetenv.html) | *    |      |
|                                                              | [fesetexceptflag()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fesetexceptflag.html) | *    |      |
|                                                              | [fesetround()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fesetround.html) | *    |      |
|                                                              | [fetestexcept()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fetestexcept.html) | *    |      |
|                                                              | [feupdateenv()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/feupdateenv.html) | *    |      |
### inttypes.h
| [<inttypes.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/inttypes.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [imaxabs()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/imaxabs.html) | *    | *    |
|                                                              | [imaxdiv()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/imaxdiv.html) | *    | *    |
|                                                              | [strtoimax()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtoimax.html) | *    | *    |
|                                                              | [strtoumax()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtoumax.html) | *    | *    |
### local.h
| [<local.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/locale.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [localeconv()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/localeconv.html) | *    |      |
|                                                              | [setlocale()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/setlocale.html) | *    |      |
### pthread.h
| [<pthread.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/pthread.h.html) |                                    |      |      |
| ------------------------------------------------------------ | ---------------------------------- | ---- | ---- |
|                                                              | pthread_attr_destroy()             | *    |      |
|                                                              | pthread_attr_getdetachstate()      | *    |      |
|                                                              | pthread_attr_getguardsize()        | *    |      |
|                                                              | pthread_attr_getinheritsched()     | *    |      |
|                                                              | pthread_attr_getschedparam()       | *    |      |
|                                                              | pthread_attr_getschedpolicy()      | *    |      |
|                                                              | pthread_attr_getscope()            | *    |      |
|                                                              | pthread_attr_getstack()            | *    |      |
|                                                              | pthread_attr_getstackaddr()        | *    |      |
|                                                              | pthread_attr_getstacksize()        | *    |      |
|                                                              | pthread_attr_init()                | *    |      |
|                                                              | pthread_attr_setdetachstate()      | *    |      |
|                                                              | pthread_attr_setguardsize()        | *    |      |
|                                                              | pthread_attr_setinheritsched()     | *    |      |
|                                                              | pthread_attr_setschedparam()       | *    |      |
|                                                              | pthread_attr_setschedpolicy()      | *    |      |
|                                                              | pthread_attr_setscope()            | *    |      |
|                                                              | pthread_attr_setstack()            | *    |      |
|                                                              | pthread_attr_setstackaddr()        | *    |      |
|                                                              | pthread_attr_setstacksize()        | *    |      |
|                                                              | pthread_cancel()                   | *    |      |
|                                                              | pthread_cleanup_pop()              | *    |      |
|                                                              | pthread_cleanup_push()             | *    |      |
|                                                              | pthread_cond_broadcast()           | *    |      |
|                                                              | pthread_cond_destroy()             | *    |      |
|                                                              | pthread_cond_init()                | *    |      |
|                                                              | pthread_cond_signal()              | *    |      |
|                                                              | pthread_cond_timedwait()           | *    |      |
|                                                              | pthread_cond_wait()                | *    |      |
|                                                              | pthread_condattr_destroy()         | *    |      |
|                                                              | pthread_condattr_getclock()        | *    |      |
|                                                              | pthread_condattr_init()            | *    |      |
|                                                              | pthread_condattr_setclock()        | *    |      |
|                                                              | pthread_create()                   | *    |      |
|                                                              | pthread_detach()                   | *    |      |
|                                                              | pthread_equal()                    | *    |      |
|                                                              | pthread_exit()                     | *    |      |
|                                                              | pthread_getconcurrency()           | *    |      |
|                                                              | pthread_getschedparam()            | *    |      |
|                                                              | pthread_getspecific()              | *    |      |
|                                                              | pthread_join()                     | *    |      |
|                                                              | pthread_key_create()               | *    |      |
|                                                              | pthread_key_delete()               | *    |      |
|                                                              | pthread_mutex_destroy()            | *    |      |
|                                                              | pthread_mutex_getprioceiling()     | *    |      |
|                                                              | pthread_mutex_init()               | *    |      |
|                                                              | pthread_mutex_lock()               | *    |      |
|                                                              | pthread_mutex_setprioceiling()     | *    |      |
|                                                              | pthread_mutex_trylock()            | *    |      |
|                                                              | pthread_mutex_unlock()             | *    |      |
|                                                              | pthread_mutexattr_destroy()        | *    |      |
|                                                              | pthread_mutexattr_getprioceiling() | *    |      |
|                                                              | pthread_mutexattr_getprotocol()    | *    |      |
|                                                              | pthread_mutexattr_gettype()        | *    |      |
|                                                              | pthread_mutexattr_init()           | *    |      |
|                                                              | pthread_mutexattr_setprioceiling() | *    |      |
|                                                              | pthread_mutexattr_setprotocol()    | *    |      |
|                                                              | pthread_mutexattr_settype()        | *    |      |
|                                                              | pthread_once()                     | *    |      |
|                                                              | pthread_self()                     | *    |      |
|                                                              | pthread_setcancelstate()           | *    |      |
|                                                              | pthread_setcanceltype()            | *    |      |
|                                                              | pthread_setconcurrency()           | *    |      |
|                                                              | pthread_setschedparam()            | *    |      |
|                                                              | pthread_setschedprio()             | *    |      |
|                                                              | pthread_setspecific()              | *    |      |
|                                                              | pthread_testcancel()               | *    |      |
|                                                              | pthread_atfork()                   | *    |      |
|                                                              | pthread_getcpuclockid()            | *    |      |
```
pthread_attr_destroy()
pthread_attr_getdetachstate()     
pthread_attr_getguardsize()       
pthread_attr_getinheritsched()    
pthread_attr_getschedparam()      
pthread_attr_getschedpolicy()     
pthread_attr_getscope()           
pthread_attr_getstack()           
pthread_attr_getstackaddr()       
pthread_attr_getstacksize()       
pthread_attr_init()               
pthread_attr_setdetachstate()     
pthread_attr_setguardsize()       
pthread_attr_setinheritsched()    
pthread_attr_setschedparam()      
pthread_attr_setschedpolicy()     
pthread_attr_setscope()           
pthread_attr_setstack()           
pthread_attr_setstackaddr()       
pthread_attr_setstacksize()       
pthread_cancel()                  
pthread_cleanup_pop()             
pthread_cleanup_push()            
pthread_cond_broadcast()          
pthread_cond_destroy()            
pthread_cond_init()               
pthread_cond_signal()             
pthread_cond_timedwait()          
pthread_cond_wait()               
pthread_condattr_destroy()        
pthread_condattr_getclock()       
pthread_condattr_init()           
pthread_condattr_setclock()       
pthread_create()                  
pthread_detach()                  
pthread_equal()                   
pthread_exit()                    
pthread_getconcurrency()          
pthread_getschedparam()           
pthread_getspecific()             
pthread_join()                    
pthread_key_create()              
pthread_key_delete()              
pthread_mutex_destroy()           
pthread_mutex_getprioceiling()    
pthread_mutex_init()              
pthread_mutex_lock()              
pthread_mutex_setprioceiling()    
pthread_mutex_trylock()           
pthread_mutex_unlock()            
pthread_mutexattr_destroy()       
pthread_mutexattr_getprioceiling()
pthread_mutexattr_getprotocol()   
pthread_mutexattr_gettype()       
pthread_mutexattr_init()          
pthread_mutexattr_setprioceiling()
pthread_mutexattr_setprotocol()   
pthread_mutexattr_settype()       
pthread_once()                    
pthread_self()                    
pthread_setcancelstate()          
pthread_setcanceltype()           
pthread_setconcurrency()          
pthread_setschedparam()           
pthread_setschedprio()            
pthread_setspecific()             
pthread_testcancel()              
pthread_atfork()                  
pthread_getcpuclockid()           
```



### sched.h

| [<sched.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/sched.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [sched_get_priority_max()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sched_get_priority_max.html) | *    |      |
|                                                              | [sched_get_priority_min()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sched_get_priority_min.html) | *    |      |
|                                                              | [sched_rr_get_interval()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sched_rr_get_interval.html) | *    |      |
### semaphore.h
| [<semaphore.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/semaphore.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [sem_close()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_close.html) | *    |      |
|                                                              | [sem_destroy()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_destroy.html) | *    |      |
|                                                              | [sem_getvalue()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_getvalue.html) | *    |      |
|                                                              | [sem_init()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_init.html) | *    |      |
|                                                              | [sem_open()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_open.html) | *    |      |
|                                                              | [sem_post()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_post.html) | *    |      |
|                                                              | [sem_timedwait()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_timedwait.html) | *    |      |
|                                                              | [sem_trywait()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_trywait.html) | *    |      |
|                                                              | [sem_unlink()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_unlink.html) | *    |      |
|                                                              | [sem_wait()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sem_wait.html) | *    |      |
### setjmp.h
| [<setjmp.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/setjmp.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [longjmp()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/longjmp.html) | *    |      |
|                                                              | [setjmp()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/setjmp.html) | *    |      |
### signal.h
| [<signal.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/signal.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [kill()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/kill.html) | *    |      |
|                                                              | [pthread_kill()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/pthread_kill.html) | *    |      |
|                                                              | [pthread_sigmask()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/pthread_sigmask.html) | *    |      |
|                                                              | [raise()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/raise.html) | *    |      |
|                                                              | [sigaction()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigaction.html) | *    |      |
|                                                              | [sigaddset()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigaddset.html) | *    |      |
|                                                              | [sigdelset()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigdelset.html) | *    |      |
|                                                              | [sigemptyset()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigemptyset.html) | *    |      |
|                                                              | [sigfillset()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigfillset.html) | *    |      |
|                                                              | [sigismember()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigismember.html) | *    |      |
|                                                              | [signal()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/signal.html) | *    |      |
|                                                              | [sigpending()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigpending.html) | *    |      |
|                                                              | [sigprocmask()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigprocmask.html) | *    |      |
|                                                              | [sigqueue()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigqueue.html) | *    |      |
|                                                              | [sigsuspend()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigsuspend.html) | *    |      |
|                                                              | [sigtimedwait()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigtimedwait.html) | *    |      |
|                                                              | [sigwait()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigwait.html) | *    |      |
|                                                              | [sigwaitinfo()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sigwaitinfo.html) | *    |      |
### stdarg.h
| [<stdarg.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/stdarg.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [va_arg()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/va_arg.html) | *    | *    |
|                                                              | [va_copy()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/va_copy.html) | *    | *    |
|                                                              | [va_end()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/va_end.html) | *    | *    |
|                                                              | [va_start()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/va_start.html) | *    | *    |
### stdio.h
| [<stdio.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/stdio.h.html) |                    |      |      |
| ------------------------------------------------------------ | ------------------ | ---- | ---- |
|                                                              | clearerr()         | *    |      |
|                                                              | fclose()           | *    |      |
|                                                              | fdopen()           | *    |      |
|                                                              | feof()             | *    |      |
|                                                              | ferror()           | *    |      |
|                                                              | fflush()           | *    |      |
|                                                              | fgetc()            | *    |      |
|                                                              | fgets()            | *    |      |
|                                                              | fileno()           | *    |      |
|                                                              | flockfile()        | *    |      |
|                                                              | fopen()            | *    |      |
|                                                              | fprintf()          | *    |      |
|                                                              | fputc()            | *    |      |
|                                                              | fputs()            | *    |      |
|                                                              | fread()            | *    |      |
|                                                              | freopen()          | *    |      |
|                                                              | fscanf()           | *    |      |
|                                                              | ftrylockfile()     | *    |      |
|                                                              | funlockfile()      | *    |      |
|                                                              | fwrite()           | *    |      |
|                                                              | getc()             | *    |      |
|                                                              | getc_unlocked()    | *    |      |
|                                                              | getchar()          | *    |      |
|                                                              | getchar_unlocked() | *    |      |
|                                                              | gets()             | *    |      |
|                                                              | perror()           | *    |      |
|                                                              | printf()           | *    |      |
|                                                              | putc()             | *    |      |
|                                                              | putc_unlocked()    | *    |      |
|                                                              | putchar()          | *    |      |
|                                                              | putchar_unlocked() | *    |      |
|                                                              | puts()             | *    |      |
|                                                              | scanf()            | *    |      |
|                                                              | setbuf()           | *    |      |
|                                                              | setvbuf()          | *    |      |
|                                                              | snprintf()         | *    |      |
|                                                              | sprintf()          | *    |      |
|                                                              | sscanf()           | *    |      |
|                                                              | stderr             | *    | *    |
|                                                              | stdin              | *    | *    |
|                                                              | stdout             | *    | *    |
|                                                              | ungetc()           | *    |      |
|                                                              | vfprintf()         | *    | *    |
|                                                              | vfscanf()          | *    |      |
|                                                              | vprintf()          | *    |      |
|                                                              | vscanf()           | *    |      |
|                                                              | vsnprintf()        | *    |      |
|                                                              | vsprintf()         | *    |      |
|                                                              | vsscanf()          | *    |      |
```
                fclose()          fdopen()          feof()            ferror()          fflush()          fgetc()           fgets()           fileno()          flockfile()       fopen()           fprintf()         fputc()           fputs()           fread()           freopen()         fscanf()          ftrylockfile()    funlockfile()     fwrite()          getc()            getc_unlocked()   getchar()         getchar_unlocked()gets()            perror()          printf()          putc()            putc_unlocked()   putchar()         putchar_unlocked()puts()            scanf()           setbuf()          setvbuf()         snprintf()        sprintf()         sscanf()          stder            stdin             stdout            ungetc()          vfprintf()        vfscanf()          vprintf()          vscanf()           vsnprintf()        vsprintf()         vsscanf()
```



### stdlib.h

| [<stdlib.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/stdlib.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [abort()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/abort.html) | *    | *    |
|                                                              | [abs()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/abs.html) | *    | *    |
|                                                              | [atof()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/atof.html) | *    | *    |
|                                                              | [atoi()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/atoi.html) | *    | *    |
|                                                              | [atol()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/atol.html) | *    | *    |
|                                                              | [atoll()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/atoll.html) | *    | *    |
|                                                              | [bsearch()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/bsearch.html) | *    | *    |
|                                                              | [calloc()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/calloc.html) | *    |      |
|                                                              | [div()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/div.html) | *    | *    |
|                                                              | [free()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/free.html) | *    |      |
|                                                              | [getenv()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/getenv.html) | *    |      |
|                                                              | [labs()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/labs.html) | *    | *    |
|                                                              | [ldiv()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/ldiv.html) | *    | *    |
|                                                              | [llabs()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/llabs.html) | *    | *    |
|                                                              | [lldiv()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/lldiv.html) | *    | *    |
|                                                              | [malloc()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/malloc.html) | *    |      |
|                                                              | [mktime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/mktime.html) | *    |      |
|                                                              | [qsort()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/qsort.html) | *    | *    |
|                                                              | [rand()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/rand.html) | *    | *    |
|                                                              | [rand_r()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/rand_r.html) | *    | *    |
|                                                              | [realloc()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/realloc.html) | *    |      |
|                                                              | [setenv()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/setenv.html) | *    |      |
|                                                              | [srand()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/srand.html) | *    | *    |
|                                                              | [strtod()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtod.html) | *    | *    |
|                                                              | [strtof()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtof.html) | *    | *    |
|                                                              | [strtol()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtol.html) | *    | *    |
|                                                              | [strtold()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtold.html) | *    | *    |
|                                                              | [strtoll()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtoll.html) | *    | *    |
|                                                              | [strtoul()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtoul.html) | *    | *    |
|                                                              | [strtoull()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtoull.html) | *    | *    |
|                                                              | [unsetenv()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/unsetenv.html) | *    |      |
### string.h
| [<string.h>](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/string.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [memchr()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/memchr.html) | *    |      |
|                                                              | [memcmp()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/memcmp.html) | *    |      |
|                                                              | [memcpy()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/memcpy.html) | *    |      |
|                                                              | [memmove()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/memmove.html) | *    |      |
|                                                              | [memset()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/memset.html) | *    |      |
|                                                              | [ strcat()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strcat.html) | *    |      |
|                                                              | [strchr()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strchr.html) | *    |      |
|                                                              | [strcmp()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strcmp.html) | *    |      |
|                                                              | [strcoll()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strcoll.html) | *    |      |
|                                                              | [strcpy()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strcpy.html) | *    |      |
|                                                              | [strcspn()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strcspn.html) | *    |      |
|                                                              | [strerror()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strerror.html) | *    |      |
|                                                              | [strerror_r()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strerror_r.html) | *    |      |
|                                                              | [strlen()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strlen.html) | *    |      |
|                                                              | [strncat()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strncat.html) | *    |      |
|                                                              | [strncmp()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strncmp.html) | *    |      |
|                                                              | [strncpy()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strncpy.html) | *    |      |
|                                                              | [strpbrk()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strpbrk.html) | *    |      |
|                                                              | [strrchr()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strrchr.html) | *    |      |
|                                                              | [strspn()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strspn.html) | *    |      |
|                                                              | [strstr()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strstr.html) | *    |      |
|                                                              | [strtok()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtok.html) | *    |      |
|                                                              | [strtok_r()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strtok_r.html) | *    |      |
|                                                              | [strxfrm()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strxfrm.html) | *    |      |
### mman.h
| [mman.h](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/sys_mman.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [mlockall()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/mlockall.html) | *    |      |
|                                                              | [mmap()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/mmap.html) | *    |      |
|                                                              | [munlock()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/munlock.html) | *    |      |
|                                                              | [munmap()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/munmap.html) | *    |      |
|                                                              | [shm_open()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/shm_open.html) | *    |      |
|                                                              | [shm_unlink()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/shm_unlink.html) | *    |      |
### uname.h
| [uname.h](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/sys_utsname.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [uname()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/uname.html) | *    |      |
### time.h
| [time.h](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/time.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [asctime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/asctime.html) | *    |      |
|                                                              | [asctime_r()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/asctime_r.html) | *    |      |
|                                                              | [clock_getres()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/clock_getres.html) | *    |      |
|                                                              | [clock_gettime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/clock_gettime.html) | *    |      |
|                                                              | [clock_nanosleep()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/clock_nanosleep.html) | *    |      |
|                                                              | [clock_settime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/clock_settime.html) | *    |      |
|                                                              | [ctime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/ctime.html) | *    |      |
|                                                              | [ctime_r()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/ctime_r.html) | *    |      |
|                                                              | [difftime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/difftime.html) | *    |      |
|                                                              | [gmtime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/gmtime.html) | *    |      |
|                                                              | [gmtime_r()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/gmtime_r.html) | *    |      |
|                                                              | [localtime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/localtime.html) | *    |      |
|                                                              | [localtime_r()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/localtime_r.html) | *    |      |
|                                                              | [nanosleep()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/nanosleep.html) | *    |      |
|                                                              | [strftime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/strftime.html) | *    |      |
|                                                              | [time()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/time.html) | *    |      |
|                                                              | [timer_create()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/timer_create.html) | *    |      |
|                                                              | [timer_delete()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/timer_delete.html) | *    |      |
|                                                              | [timer_getoverrun()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/timer_getoverrun.html) | *    |      |
|                                                              | [timer_gettime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/timer_gettime.html) | *    |      |
|                                                              | [timer_settime()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/timer_settime.html) | *    |      |
|                                                              | [tzname](https://pubs.opengroup.org/onlinepubs/9699919799/functions/tzname.html) | *    |      |
|                                                              | [tzset()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/tzset.html) | *    |      |
### unistd.h
| [unistd.h](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/unistd.h.html) |                                                              |      |      |
| ---- | ---- | ---- | ---- |
|                                                              | [alarm()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/alarm.html) | *    |      |
|                                                              | [close()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/close.html) | *    |      |
|                                                              | [environ](https://pubs.opengroup.org/onlinepubs/9699919799/functions/environ.html) | *    |      |
|                                                              | [fdatasync()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fdatasync.html) | *    |      |
|                                                              | [fsync()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/fsync.html) | *    |      |
|                                                              | [pause()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/pause.html) | *    |      |
|                                                              | [read()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/read.html) | *    |      |
|                                                              | [sysconf()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/sysconf.html) | *    |      |
|                                                              | [write()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/write.html) | *    |      |
|                                                              | [confstr()](https://pubs.opengroup.org/onlinepubs/9699919799/functions/confstr.html) | *    |      |


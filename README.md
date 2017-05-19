# {
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {
    "collapsed": false
   },
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Здравствуй, дивный новый мир!\n"
     ]
    }
   ],
   "source": [
    "print 'Здравствуй, дивный новый мир!'"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Есть данные в БД Oracle. Есть рабочий скрипт. Было бы неплохо создать портал, где человек смог бы сам запускать через браузер этот скрипт, не трогая меня!\n",
    "\n",
    "Директор департамента хочет видеть KPI на еженедельной основе. Хочу ему сделать портал с графиками, которые будут обновляться по понедельникам\n",
    "\n",
    "Когда сделаю первые две задачи, то хочу создать экпертную систему, которая будет проводить по дереву вопросов пользователя и давать ему ответ"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "metadata": {
    "collapsed": false
   },
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "154805.63583\n"
     ]
    }
   ],
   "source": [
    "s = 200000\n",
    "p = 0.08\n",
    "f = 12\n",
    "l = 5\n",
    "\n",
    "print (s*(1+(p/100*f))**(f*l)-s)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "metadata": {
    "collapsed": false
   },
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "801.28102441\n"
     ]
    }
   ],
   "source": [
    "s = 200000\n",
    "p = 0.08\n",
    "f = 1\n",
    "l = 5\n",
    "\n",
    "print (s*(1+(p/100*f))**(f*l)-s)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 2",
   "language": "python",
   "name": "python2"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 2
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython2",
   "version": "2.7.13"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}

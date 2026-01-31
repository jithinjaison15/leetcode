class Solution(object):
    def isPowerOfThree(self, n):
        """
        :type n: int
        :rtype: bool
        """
        if n <= 0:
            return False

        x = 0
        while 3 ** x <= n:
            if n == 3 ** x:
                return True
            x += 1

        return False

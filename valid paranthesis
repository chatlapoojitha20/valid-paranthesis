class Solution(object):
    def isValid(self, s):
        """
        :type s: str
        :rtype: bool
        """
        stack=[]
        for i in s:
            if(i in "({["):
                stack.append(i)
            else:
                if(len(stack)==0):
                    return False
                X=stack.pop()
                if(X=="(" and i==")"or X=="{" and i=="}" or X=="[" and i=="]"):
                    continue
                else:
                    return False

                return len(stack)==

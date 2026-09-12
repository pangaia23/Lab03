# Example
def chat_task(ctx, pipe, n, group): # function name is chat_task
def get_peer_node(username): # function name is get_peer_node
  username # I assume this is your username that we'll get from our get_username function
# This function return something that looks like a Pyre Node to me (my peer node?)

def join_group(node, group): # function name join_group
  node # I assume this is my peer computer node
  group # I assume this is a group that I want to join from our get_group function
# This function returns Nothing Lebowski!
def get_channel(node, group): # function name get_channela
  node # I assume this is my peer computer node
  group # I assume this is a group that I want to join similar to join_group
# Yes it returns a zhelper, Not sure what that is, but maybe a channel
ctx: This is a ZeroMQ Connection Context
pipe: This is a communications pipe polled by ZeroMQ for messages.
n: This is the peer to peer node my chat app is connected as
group: This is the peer chat group I wanted to join
# Example
The chat_task method does not return anything, it appears to be the send/recieve manager.

.. Tezos documentation master file, created by
   sphinx-quickstart on Sat Nov 11 11:08:48 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


Welcome to the Tezos Developer Documentation!
=============================================

Tezos is a distributed consensus platform with meta-consensus
capability. Tezos not only comes to consensus about the state of its ledger,
like Bitcoin or Ethereum. It also attempts to come to consensus about how the
protocol and the nodes should adapt and upgrade.

 - Developer documentation is available online at http://tezos.gitlab.io/master
   always in sync with the master branch (which may be desynchronized with
   the code running on the live networks, replace ``master`` in the URL by the
   branch of your choice: betanet, alphanet, zeronet, to make sure you are
   consulting the right API version)
 - The official Tezos website https://tezos.com/ contains more information about the
   project.
 - All development now happens on GitLab at https://gitlab.com/tezos/tezos

The Tezos Alpha (test) network has been live and open since February 2017.

The Tezos Beta (experimental) network has been live and open since June 2018.


 - More information on joining the Alphanet at :ref:`here <alphanet>`.
 - Several community built block explorers are available:

    - http://ostez.com
    - http://tzscan.io
    - https://tezos.id

- A few community run websites collect useful Tezos links:

    - https://www.tezos.help
    - https://tezos.rocks

 - There is a matrix channel *Tezos* that you can join `here <https://riot.im/app/#/room/#tezos:matrix.org>`_.
 - There is a *#tezos* channel on *freenode* that is reserved for technical discussions
 - There is also a community FAQ at https://github.com/tezoscommunity/faq/wiki/Tezos-Technical-FAQ

The source code of Tezos is placed under the MIT Open Source License.

.. toctree::
   :maxdepth: 2
   :caption: Introduction:

   introduction/howto
   introduction/contributing

.. toctree::
   :maxdepth: 2
   :caption: Test Networks:

   introduction/alphanet
   introduction/zeronet

.. toctree::
   :maxdepth: 2
   :caption: White doc:

   whitedoc/the_big_picture
   whitedoc/p2p
   whitedoc/validation
   whitedoc/michelson
   whitedoc/proof_of_stake

.. toctree::
   :maxdepth: 2
   :caption: Developer Tutorials:

   tutorials/data_encoding
   tutorials/error_monad
   tutorials/michelson_anti_patterns
   tutorials/entering_alpha
   tutorials/protocol_environment
   tutorials/profiling

.. toctree::
   :maxdepth: 2
   :caption: APIs:

   README
   api/api-inline
   api/cli-commands
   api/rpc
   api/errors

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

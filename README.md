# Chat_with_webpages_using_langchain
Chat_with_webpages is a Python program built on the LangChain framework, enabling users to extract information from webpages provided as URLs and engage in conversational question answering with a responsive chatbot interface. It utilizes natural language processing to understand user queries and provides relevant answers based on the content. With this tool, users can interact with a chatbot interface to obtain relevant answers pertaining to the content of the provided webpage.

## Features
    -Seamless integration with the LangChain framework.
    -Ability to extract and analyze content from a specified webpage URL.
    -Natural language processing capabilities for understanding user queries.
    -Responsive chatbot interface for interactive communication.
    -Efficient question answering based on the content of the provided webpage.

## Note:
    -if following Error exists:
        -Your system has an unsupported version of sqlite3. Chroma requires sqlite3 >= 3.35.0.
            #Paste this line in .venv path(.venv/lib/python3.11/site-packages/chromadb/__init__.py)
            '''
            (line 67)
            if sqlite3.sqlite_version_info < (3, 35, 0):
                    __import__('pysqlite3')
                    import sys
                    sys.modules['sqlite3'] = sys.modules.pop('pysqlite3')
            '''

        -USER_AGENT environment variable not set, consider setting it to identify your requests.
            -Write in terminal export USER_AGENT="Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:89.0) Gecko/20100101 Firefox/89.0"
            -or write it in your env file: USER_AGENT="Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:89.0) Gecko/20100101 Firefox/89.0"

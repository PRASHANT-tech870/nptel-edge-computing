import React, { useState, useEffect } from 'react';
import { Shuffle } from 'lucide-react';

const QuizApp = () => {
  // All questions from the documents
  const allQuestions = [
    {
      question: "Which company introduced EC2, a service for on-demand computing?",
      options: ["Microsoft", "Google", "Amazon", "Oracle"],
      answer: "Amazon"
    },
    {
      question: "What defines the 'intelligence tier' in edge computing architecture?",
      options: ["Data ingestion", "Running ML models", "Data storage", "User interfaces"],
      answer: "Running ML models"
    },
    {
      question: "What is the main benefit of virtualization in cloud computing?",
      options: ["High latency", "Cost increase", "Efficient resource utilization", "Limited scalability"],
      answer: "Efficient resource utilization"
    },
    {
      question: "Which cloud service model includes virtual machines, storage, and networking capabilities?",
      options: ["IaaS", "PaaS", "SaaS", "HaaS"],
      answer: "IaaS"
    },
    {
      question: "According to Moore's Law, processor speed doubles every:",
      options: ["9 months", "12 months", "18 months", "24 months"],
      answer: "18 months"
    },
    {
      question: "What does the Water Usage Effectiveness (WUE) metric measure in cloud data centers?",
      options: ["IT energy consumption per server", "Total facility power to IT power ratio", "Annual water usage per IT equipment energy", "Data transmission speed per watt"],
      answer: "Annual water usage per IT equipment energy"
    },
    {
      question: "Identify the correct match:",
      options: ["IaaS – Load Balancing", "PaaS – Virtual Machines", "SaaS – Web Servers", "HaaS – CRM"],
      answer: "IaaS – Load Balancing"
    },
    {
      question: "If an edge node takes 0.05 seconds to process a task and 0.02 seconds for data transfer, what is the total latency?",
      options: ["0.07 seconds", "0.05 seconds", "0.02 seconds", "0.09 seconds"],
      answer: "0.07 seconds"
    },
    {
      question: "Which cloud computing model primarily provides runtime environments, databases, and development tools?",
      options: ["SaaS", "IaaS", "PaaS", "HaaS"],
      answer: "PaaS"
    },
    {
      question: "Which cloud computing paradigm enables customers to access virtual machines, servers, and storage on a pay-as-you-go basis?",
      options: ["SaaS", "PaaS", "IaaS", "HaaS"],
      answer: "IaaS"
    },
    {
      question: "Which type of hypervisor runs directly on hardware without an operating system?",
      options: ["Type-I (Bare-metal)", "Type-II (Hosted)", "Hybrid", "None of the above"],
      answer: "Type-I (Bare-metal)"
    },
    {
      question: "Which metric measures the energy efficiency of data centers?",
      options: ["PUE", "WUE", "ROI", "SLA"],
      answer: "PUE"
    },
    {
      question: "What is Docker primarily used for?",
      options: ["Network monitoring", "Container-based virtualization", "File management", "Hardware emulation"],
      answer: "Container-based virtualization"
    },
    {
      question: "What is one key benefit of containerization compared to virtual machines?",
      options: ["Faster startup times", "Stronger isolation", "Requires more resources", "Slower deployment"],
      answer: "Faster startup times"
    },
    {
      question: "How much time will it take to upload 10 GB of data over a network with a speed of 10 Mbps?",
      options: ["~10 minutes", "~13.3 minutes", "~16.7 minutes", "~20 minutes"],
      answer: "~13.3 minutes"
    },
    {
      question: "In hardware virtualization, what is the role of Intel VT or AMD-V extensions?",
      options: ["Improve energy efficiency", "Support for binary translation", "Enable the hypervisor to run guest OS in isolation", "Allow faster disk access"],
      answer: "Enable the hypervisor to run guest OS in isolation"
    },
    {
      question: "Which of the following is a benefit of Docker over traditional VMs?",
      options: ["Requires its own kernel for each instance", "Faster scaling and portability", "Stronger isolation than VMs", "High resource consumption"],
      answer: "Faster scaling and portability"
    },
    {
      question: "Which is a characteristic of paravirtualization?",
      options: ["Guest OS requires no modification", "Uses a thin VMM and requires hyper calls", "Fully emulates hardware", "Higher overhead than full virtualization"],
      answer: "Uses a thin VMM and requires hyper calls"
    },
    {
      question: "Which virtualization technique involves modifying the guest OS for better interaction with the hypervisor?",
      options: ["Para-virtualization", "Full virtualization", "Partial virtualization", "Application-level virtualization"],
      answer: "Para-virtualization"
    },
    {
      question: "What is the smallest deployable unit in Kubernetes?",
      options: ["Pod", "Node", "Container", "Cluster"],
      answer: "Pod"
    },
    {
      question: "What does Kubernetes primarily manage in a containerized environment?",
      options: ["Physical servers", "Container orchestration", "Virtual machines", "Data encryption"],
      answer: "Container orchestration"
    },
    {
      question: "If a Kubernetes deployment specifies 5 replicas for a Pod, how many Pods will be running if 2 nodes fail in a cluster of 10 nodes?",
      options: ["3", "5", "7", "0"],
      answer: "5"
    },
    {
      question: "Which of the following is NOT a core component of the Kubernetes Control Plane?",
      options: ["API Server", "kube-proxy", "Scheduler", "Controller Manager"],
      answer: "kube-proxy"
    },
    {
      question: "What is the function of a Namespace in Kubernetes?",
      options: ["Group and isolate cluster resources", "Perform health checks on containers", "Automate node scaling", "Monitor cluster metrics"],
      answer: "Group and isolate cluster resources"
    },
    {
      question: "What is the primary purpose of the kube-proxy?",
      options: ["Monitor node health", "Store data persistently", "Provide network load balancing", "Manage application configurations"],
      answer: "Provide network load balancing"
    },
    {
      question: "If a Service in Kubernetes balances traffic across 4 Pods, and each Pod handles 100 requests per second, what is the total throughput of the Service?",
      options: ["100 requests/second", "200 requests/second", "300 requests/second", "400 requests/second"],
      answer: "400 requests/second"
    },
    {
      question: "If a Deployment specifies a rolling update strategy with maxUnavailable: 1 and there are 10 replicas, how many Pods will remain available during the update?",
      options: ["7", "8", "9", "10"],
      answer: "9"
    },
    {
      question: "What is the function of the Kubernetes Scheduler?",
      options: ["Monitor Pod health", "Assign Pods to suitable nodes", "Store cluster state in etcd", "Expose Pods to external traffic"],
      answer: "Assign Pods to suitable nodes"
    },
    {
      question: "How many replicas will be created if a Deployment is configured with replicas: 4?",
      options: ["2", "3", "4", "5"],
      answer: "4"
    },
    {
      question: "Which algorithm is used to aggregate models in Federated Learning?",
      options: ["Backpropagation", "FedAvg", "K-means", "Principal Component Analysis"],
      answer: "FedAvg"
    },
    {
      question: "What is one major advantage of Federated Learning for IoT devices?",
      options: ["Reduced hardware requirements", "Simplified data preprocessing", "Data privacy and decentralized training", "Increased computational speed"],
      answer: "Data privacy and decentralized training"
    },
    {
      question: "In knowledge distillation, which loss function is used to transfer knowledge from teacher to student?",
      options: ["Mean Squared Error (MSE)", "Hinge Loss", "Cross-Entropy", "KL Divergence"],
      answer: "KL Divergence"
    },
    {
      question: "What is the primary challenge of non-IID (independent and identically distributed) data in FL?",
      options: ["Data leakage", "Higher computational costs", "Slower convergence of the model", "Model overfitting"],
      answer: "Slower convergence of the model"
    },
    {
      question: "What is the primary benefit of low-rank factorization in deep learning model optimization?",
      options: ["Reduces model size and computation costs", "Increases model accuracy", "Improves training speed", "Enhances data privacy"],
      answer: "Reduces model size and computation costs"
    },
    {
      question: "In Federated Learning, if a cluster has 4 devices and each device achieves an accuracy of 80%, what is the average accuracy of the aggregated model?",
      options: ["20%", "40%", "100%", "80%"],
      answer: "80%"
    },
    {
      question: "What is a critical privacy concern in Federated Learning?",
      options: ["Membership inference attacks", "Model convergence speed", "Computational power", "Network bandwidth"],
      answer: "Membership inference attacks"
    },
    {
      question: "A Federated Learning model sends updates to the central server every 5 seconds. How many updates are sent in 1 minute?",
      options: ["10", "12", "15", "20"],
      answer: "12"
    },
    {
      question: "In Knowledge Distillation, which of the following is considered the \"teacher\"?",
      options: ["A smaller, simplified model", "The dataset used for training", "A large, pre-trained model", "The optimizer used during training"],
      answer: "A large, pre-trained model"
    },
    {
      question: "What challenge in Federated Learning does the term \"non-IID data\" refer to?",
      options: ["High bandwidth usage during model training", "Data being unevenly distributed and diverse across devices", "Lack of encryption for sensitive data", "Overfitting due to excessive training"],
      answer: "Data being unevenly distributed and diverse across devices"
    },
    {
      question: "How is the resource allocation problem in Collaborative Edge-Cloud computing modeled to optimize long-term objectives?",
      options: ["As a static optimization problem using linear programming.", "As a deterministic system solved using brute force methods.", "As a Markov Decision Process (MDP) for reward maximization.", "As a purely heuristic problem with no mathematical framework"],
      answer: "As a Markov Decision Process (MDP) for reward maximization."
    },
    {
      question: "In MEC, what is horizontal offloading?",
      options: ["Distributing tasks across multiple edge servers", "Transferring tasks to a cloud server", "Offloading tasks locally", "Processing tasks sequentially"],
      answer: "Distributing tasks across multiple edge servers"
    },
    {
      question: "If the local execution delay for a task is 0.02 seconds and the remote execution delay is 0.015 seconds, should the task be offloaded?",
      options: ["Yes", "No", "Only for partial offloading", "Depends on network conditions"],
      answer: "Yes"
    },
    {
      question: "Which of the following influences task offloading decisions in MEC?",
      options: ["Network latency", "User preferences", "Device mobility", "All of the above"],
      answer: "All of the above"
    },
    {
      question: "What is the primary difference between vertical and horizontal offloading?",
      options: ["Vertical offloading moves tasks between similar resources, while horizontal distributes across edge servers.", "Vertical offloading moves tasks to higher-level resources, while horizontal distributes across similar nodes.", "Vertical offloading reduces bandwidth, while horizontal increases it.", "Horizontal offloading is only used in cloud computing."],
      answer: "Vertical offloading moves tasks to higher-level resources, while horizontal distributes across similar nodes."
    },
    {
      question: "Which MEC architecture model is characterized by deploying cloud capabilities at small cells?",
      options: ["Small Cell Cloud (SCC)", "Mobile Micro Cloud (MMC)", "ETSI MEC", "Fast Moving Personal Cloud"],
      answer: "Small Cell Cloud (SCC)"
    },
    {
      question: "A task requires 1,000,000 bits to be transmitted to an MEC server with a bandwidth of 10 Mbps. What is the transmission time?",
      options: ["0.01 seconds", "1 second", "10 seconds", "0.1 seconds"],
      answer: "0.1 seconds"
    },
    {
      question: "What is the primary goal of Mobile Edge Computing (MEC)?",
      options: ["Enhance mobile battery life", "Reduce latency and improve bandwidth", "Replace cloud computing", "Minimize data storage requirements"],
      answer: "Reduce latency and improve bandwidth"
    },
    {
      question: "What is the main advantage of dynamic resource allocation in MEC?",
      options: ["Simplified implementation", "Increased static efficiency", "Better handling of varying workloads", "Reduced energy efficiency"],
      answer: "Better handling of varying workloads"
    },
    {
      question: "Which entity in MEC architecture provides computing resources and storage at the edge?",
      options: ["Cloud server", "MEC server", "User Equipment (UE)", "Base Station"],
      answer: "MEC server"
    },
    {
      question: "Which algorithm can synchronize clocks in a distributed system using a master process to average offsets?",
      options: ["Christian's Algorithm", "NTP", "Berkley's Algorithm", "DTP"],
      answer: "Berkley's Algorithm"
    },
    {
      question: "What problem is solved by using logical clocks in distributed systems?",
      options: ["Message loss recovery", "Event ordering across processes", "Reducing memory usage", "Faster message transmission"],
      answer: "Event ordering across processes"
    },
    {
      question: "What does the term \"external synchronization\" imply in distributed systems?",
      options: ["All clocks are synchronized to a single external reference", "Clocks are synchronized relative to each other", "Clocks are not synchronized", "Each process maintains its local time independently"],
      answer: "All clocks are synchronized to a single external reference"
    },
    {
      question: "Which relationship between events is established by Lamport Timestamps?",
      options: ["Happens-before relationship", "Total ordering", "Concurrent event relationship", "Absolute event timing"],
      answer: "Happens-before relationship"
    },
    {
      question: "What is the maximum drift between two clocks if each has a maximum drift rate of 5 ms per second?",
      options: ["5 ms", "10 ms", "15 ms", "20 ms"],
      answer: "10 ms"
    },
    {
      question: "Which protocol is widely used for clock synchronization in distributed systems?",
      options: ["FTP", "FTTP", "NTP", "TCP"],
      answer: "NTP"
    },
    {
      question: "What rule does Lamport Timestamps use for assigning timestamps to events in the same process?",
      options: ["The timestamp is incremented by 2 for each event", "The timestamp is always set to 1", "The timestamp is decremented by 1 for each event", "The timestamp is incremented by 1 for each event"],
      answer: "The timestamp is incremented by 1 for each event"
    },
    {
      question: "Which technology does Google's B4 use for traffic engineering?",
      options: ["MPLS", "Software-defined networking (SDN)", "Virtual LAN", "Internet Protocol (IP)"],
      answer: "Software-defined networking (SDN)"
    },
    {
      question: "What is the main purpose of vector timestamps in distributed systems?",
      options: ["To detect and manage concurrent events", "To synchronize physical clocks", "To replace logical clocks", "To reduce network latency"],
      answer: "To detect and manage concurrent events"
    },
    {
      question: "Which of the following algorithms is used for external time synchronization in distributed systems?",
      options: ["Berkeley Algorithm", "Lamport Timestamps", "Paxos", "Christian's Algorithm"],
      answer: "Christian's Algorithm"
    },
    {
      question: "Which attack exploits communication signals in edge computing to infer sensitive data?",
      options: ["Malware injection", "Authentication bypass", "DDoS attack", "Side-channel attack"],
      answer: "Side-channel attack"
    },
    {
      question: "What is the main weakness of coarse-grained access control in MEC systems?",
      options: ["High resource consumption", "Complex configuration", "Lack of flexibility for specific permissions", "Incompatibility with cloud systems"],
      answer: "Lack of flexibility for specific permissions"
    },
    {
      question: "If a side-channel attack observes power consumption data every 10 ms and collects 100 samples, how long does the attack run?",
      options: ["1 second", "10 seconds", "100 seconds", "0.1 second"],
      answer: "1 second"
    },
    {
      question: "A server mitigates a flooding-based attack by filtering 75% of 10,000 incoming packets per second. How many packets per second reach the server?",
      options: ["7,500", "5,000", "10,000", "2,500"],
      answer: "2,500"
    },
    {
      question: "What is the primary goal of overprivileged attacks in IoT systems?",
      options: ["To exploit network vulnerabilities", "To access unauthorized resources", "To overload server hardware", "To modify encryption keys"],
      answer: "To access unauthorized resources"
    },
    {
      question: "In flooding-based attacks, which protocol is exploited in a SYN flood attack?",
      options: ["TCP", "UDP", "ICMP", "FTP"],
      answer: "TCP"
    },
    {
      question: "An edge server processes 1,000 legitimate requests per second but faces a DDoS attack with 5,000 malicious requests per second. What percentage of the total requests are legitimate?",
      options: ["20%", "50%", "16.67%", "10%"],
      answer: "16.67%"
    },
    {
      question: "Which defense mechanism prevents brute-force attacks on authentication systems?",
      options: ["Deep Packet Inspection", "Two-Factor Authentication", "Role-Based Access Control", "Dynamic Code Obfuscation"],
      answer: "Two-Factor Authentication"
    },
    {
      question: "What kind of malware targets IoT devices by exploiting their firmware vulnerabilities?",
      options: ["Ransomware", "IoT Reaper", "Spyware", "Rootkit"],
      answer: "IoT Reaper"
    },
    {
      question: "Which of the following is a key vulnerability exploited in Zero-Day DDoS attacks?",
      options: ["Protocol design flaws", "Firmware bugs", "Unknown code-level vulnerabilities", "Insufficient bandwidth"],
      answer: "Unknown code-level vulnerabilities"
    },
    {
      question: "What distinguishes Context as a Service (CaaS) from On-Demand Data Processing (ODP) in edge computing?",
      options: ["ODP processes data in a batch-processing model, while CaaS processes data in real-time.", "ODP provides pre-installed methods for request/response processing, while CaaS offers customized data provision methods.", "ODP is exclusively for SaaS providers, while CaaS is exclusively for IaaS providers.", "ODP focuses on permanent data storage, while CaaS is limited to temporary data analysis"],
      answer: "ODP provides pre-installed methods for request/response processing, while CaaS offers customized data provision methods."
    },
    {
      question: "What is the primary advantage of using GPUs in edge computing?",
      options: ["Reducing network latency", "Increasing data storage", "Accelerating machine learning computations", "Simplifying software deployment"],
      answer: "Accelerating machine learning computations"
    },
    {
      question: "Which algorithm is used for long-term optimal resource allocation in edge-cloud systems?",
      options: ["Genetic Algorithm", "Markov Decision Process (MDP)", "Linear Regression", "Naive Bayes"],
      answer: "Markov Decision Process (MDP)"
    },
    {
      question: "How does computing acceleration in edge computing improve performance?",
      options: ["By using caching to speed up the delivery of multimedia content.", "By using GPUs and FPGAs for faster computation and flexibility in program deployment.", "By creating dynamic routing paths for data transmission.", "By optimizing power consumption in IoT devices."],
      answer: "By using GPUs and FPGAs for faster computation and flexibility in program deployment."
    },
    {
      question: "Which task offloading objective focuses on balancing computational loads across servers?",
      options: ["Load Balance", "Data Variety", "Device Mobility", "Privacy Preservation"],
      answer: "Load Balance"
    },
    {
      question: "What is a key feature of networking acceleration in edge computing?",
      options: ["Edge nodes use network virtualization to enable multiple routing tables and software defined networking (SDN).", "Edge nodes rely on GPUs and FPGAs for fast inferencing and computation.", "Edge nodes enable fast processing by providing caching for content delivery.", "Edge nodes ensure the secure transfer of data streams between IoT devices and the cloud"],
      answer: "Edge nodes use network virtualization to enable multiple routing tables and software defined networking (SDN)."
    },
    {
      question: "What does the record list H in edge-cloud computing track?",
      options: ["The total cost of computation", "The history of resource allocations", "The number of active users", "The remaining VMs in each time slot"],
      answer: "The history of resource allocations"
    },
    {
      question: "What is the primary goal of Collaborative Edge-Cloud (CEC) computing?",
      options: ["To maximize data redundancy", "To minimize long-term operation costs while meeting user demands", "To eliminate the need for public cloud services", "To improve the security of cloud storage"],
      answer: "To minimize long-term operation costs while meeting user demands"
    },
    {
      question: "Which pricing mode in public cloud provides the lowest cost for users with predictable, long-term demands?",
      options: ["On-Demand Instance", "Dynamic Pricing", "Spot Instance", "Reserved Instance"],
      answer: "Reserved Instance"
    }
  ];

  // State management
  const [questions, setQuestions] = useState([]);
  const [currentQuestionIndex, setCurrentQuestionIndex] = useState(0);
  const [selectedAnswer, setSelectedAnswer] = useState(null);
  const [isAnswered, setIsAnswered] = useState(false);
  const [score, setScore] = useState(0);
  const [totalAnswered, setTotalAnswered] = useState(0);

  // Fisher-Yates shuffle algorithm
  const shuffleArray = (array) => {
    let newArray = [...array];
    for (let i = newArray.length - 1; i > 0; i--) {
      const j = Math.floor(Math.random() * (i + 1));
      [newArray[i], newArray[j]] = [newArray[j], newArray[i]];
    }
    return newArray;
  };

  // Initialize questions on component mount
  useEffect(() => {
    // Shuffle questions and their options
    shuffleQuestions();
  }, []);

  // Shuffle questions and their options
  const shuffleQuestions = () => {
    const shuffledQuestions = shuffleArray(allQuestions).map(q => {
      // Create a copy of options and shuffle them
      const shuffledOptions = shuffleArray([...q.options]);
      return {
        ...q,
        options: shuffledOptions
      };
    });
    
    setQuestions(shuffledQuestions);
    setCurrentQuestionIndex(0);
    setSelectedAnswer(null);
    setIsAnswered(false);
  };

  // Handle answer selection
  const handleSelectAnswer = (answer) => {
    if (!isAnswered) {
      setSelectedAnswer(answer);
      setIsAnswered(true);
      
      // Update score if correct
      if (answer === questions[currentQuestionIndex].answer) {
        setScore(prev => prev + 1);
      }
      
      setTotalAnswered(prev => prev + 1);
    }
  };

  // Move to next question
  const handleNextQuestion = () => {
    if (currentQuestionIndex < questions.length - 1) {
      setCurrentQuestionIndex(prev => prev + 1);
      setSelectedAnswer(null);
      setIsAnswered(false);
    }
  };

  // Move to previous question
  const handlePrevQuestion = () => {
    if (currentQuestionIndex > 0) {
      setCurrentQuestionIndex(prev => prev - 1);
      setSelectedAnswer(null);
      setIsAnswered(false);
    }
  };

  // Reset quiz
  const handleResetQuiz = () => {
    setCurrentQuestionIndex(0);
    setSelectedAnswer(null);
    setIsAnswered(false);
    setScore(0);
    setTotalAnswered(0);
  };

  // Shuffle just the options for the current question
  const shuffleCurrentOptions = () => {
    if (isAnswered) return; // Don't shuffle if already answered
    
    const newQuestions = [...questions];
    newQuestions[currentQuestionIndex] = {
      ...newQuestions[currentQuestionIndex],
      options: shuffleArray([...newQuestions[currentQuestionIndex].options])
    };
    
    setQuestions(newQuestions);
  };

  // Return empty div if questions haven't loaded yet
  if (questions.length === 0) {
    return <div className="flex items-center justify-center h-screen">Loading questions...</div>;
  }

  const currentQuestion = questions[currentQuestionIndex];

  return (
    <div className="min-h-screen bg-gray-100 p-4">
      <div className="max-w-4xl mx-auto bg-white rounded-lg shadow-md p-6">
        {/* Header section */}
        <div className="flex justify-between items-center mb-6">
          <h1 className="text-2xl font-bold text-gray-800">Cloud Computing Quiz</h1>
          <div className="flex space-x-2">
            <button 
              onClick={shuffleQuestions}
              className="flex items-center px-4 py-2 bg-blue-600 text-white rounded hover:bg-blue-700 transition-colors"
            >
              <Shuffle className="mr-2 h-4 w-4" />
              Shuffle All
            </button>
            <button 
              onClick={shuffleCurrentOptions}
              className="flex items-center px-4 py-2 bg-purple-600 text-white rounded hover:bg-purple-700 transition-colors"
              disabled={isAnswered}
            >
              <Shuffle className="mr-2 h-4 w-4" />
              Shuffle Options
            </button>
          </div>
        </div>
        
        {/* Progress indicators */}
        <div className="mb-4 flex justify-between items-center">
          <div className="text-sm text-gray-500">
            Question {currentQuestionIndex + 1} of {questions.length}
          </div>
          <div className="text-sm font-medium">
            Score: {score}/{totalAnswered} ({totalAnswered > 0 ? Math.round((score/totalAnswered) * 100) : 0}%)
          </div>
        </div>
        
        {/* Progress bar */}
        <div className="w-full bg-gray-200 rounded-full h-2.5 mb-6">
          <div 
            className="bg-blue-600 h-2.5 rounded-full" 
            style={{ width: `${((currentQuestionIndex + 1) / questions.length) * 100}%` }}
          ></div>
        </div>

        {/* Question */}
        <div className="mb-6">
          <h2 className="text-xl font-semibold mb-4">{currentQuestion.question}</h2>
          
          {/* Answer options */}
          <div className="space-y-3">
            {currentQuestion.options.map((option, index) => (
              <button
                key={index}
                onClick={() => handleSelectAnswer(option)}
                disabled={isAnswered}
                className={`w-full text-left p-4 rounded-lg border transition-colors ${
                  isAnswered && option === currentQuestion.answer 
                    ? 'bg-green-100 border-green-500' 
                    : isAnswered && option === selectedAnswer && option !== currentQuestion.answer 
                    ? 'bg-red-100 border-red-500'
                    : selectedAnswer === option
                    ? 'bg-blue-100 border-blue-500'
                    : 'bg-white border-gray-300 hover:bg-gray-50'
                }`}
              >
                {option}
              </button>
            ))}
          </div>
        </div>

        {/* Feedback when answered */}
        {isAnswered && (
          <div className={`p-4 mb-6 rounded-lg ${
            selectedAnswer === currentQuestion.answer ? 'bg-green-100 text-green-800' : 'bg-red-100 text-red-800'
          }`}>
            {selectedAnswer === currentQuestion.answer 
              ? 'Correct!' 
              : `Incorrect. The correct answer is: ${currentQuestion.answer}`
            }
          </div>
        )}

        {/* Navigation buttons */}
        <div className="flex justify-between mt-6">
          <button
            onClick={handlePrevQuestion}
            disabled={currentQuestionIndex === 0}
            className="px-6 py-2 bg-gray-200 text-gray-800 rounded hover:bg-gray-300 disabled:opacity-50 transition-colors"
          >
            Previous
          </button>
          
          <button
            onClick={handleResetQuiz}
            className="px-6 py-2 bg-yellow-500 text-white rounded hover:bg-yellow-600 transition-colors"
          >
            Reset Quiz
          </button>
          
          <button
            onClick={handleNextQuestion}
            disabled={currentQuestionIndex === questions.length - 1 || !isAnswered}
            className="px-6 py-2 bg-blue-600 text-white rounded hover:bg-blue-700 disabled:opacity-50 transition-colors"
          >
            Next
          </button>
        </div>
      </div>
    </div>
  );
};

export default QuizApp;
